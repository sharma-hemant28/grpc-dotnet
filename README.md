# grpc-dotnet
Sample project demonstrating gRPC with ASP.NET Core and .NET 9. Includes a gRPC server and client, Protobuf service definitions, and examples of unary and streaming RPCs. Follows clean architecture and modern .NET development practices.

## 📦 Features

- ASP.NET Core gRPC server
- .NET gRPC client using `Grpc.Net.Client`
- Protobuf-based strongly-typed contracts
- Unary and streaming RPC examples
- Clean architecture with DI and logging
- Docker-friendly setup

## 🚀 Getting Started

### Prerequisites

- [.NET 9 SDK](https://dotnet.microsoft.com/download)
- [Docker](https://www.docker.com/) (optional for containerized setup)

### Running the Server

```bash
cd GrpcGreeter
dotnet run

Running the Client
cd GrpcGreeterClient
dotnet run

🛠 Project Structure
grpc-dotnet/
│
├── GrpcGreeter/       	# gRPC Server implementation
├── GrpcGreeterClient/	# gRPC Client implementation
└── Protos/           	# .proto files
