# Protobuf for CSharp


<!-- TOC depthfrom:2 -->

- [Protobuf for CSharp](#protobuf-for-csharp)
  - [Simple `employee.proto`](#simple-employeeproto)
    - [Using `protoc`](#using-protoc)
    - [Using `buf`](#using-buf)
    - [Using Visual Studio](#using-visual-studio)
  - [Initiated Spark submodule](#initiated-spark-submodule)
  - [Spark Connect](#spark-connect)

<!-- /TOC -->

## Simple `employee.proto`

### Using `protoc`

* Download from [here](https://github.com/protocolbuffers/protobuf/releases/download/v21.5/protoc-21.5-win64.zip).
* Unzip it

```powershell
cd "C:\Users\mdrrahman\Downloads\protoc-21.5-win64\bin"

$SOLUTION_SRC="E:/git/protobuf-csharp/ProtoSpark/Generated/"
$PROTO_FILE="E:/git/protobuf-csharp/ProtoSpark/Proto/employee.proto"

./protoc.exe --csharp_out=$SOLUTION_SRC --proto_path=E:/git/protobuf-csharp/ProtoSpark/Proto/ $PROTO_FILE
```

This will generate `E:\git\protobuf-csharp\ProtoSpark\Generated\Employee.cs`.

### Using `buf`

`TODO`

### Using Visual Studio

`TODO`


## Initiated Spark submodule

```powershell
git submodule add https://github.com/apache/spark
```

## Spark Connect

`TODO`