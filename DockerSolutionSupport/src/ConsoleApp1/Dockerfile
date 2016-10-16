FROM microsoft/dotnet:1.0.1-core
ARG source
WORKDIR /app
COPY $source .
ENTRYPOINT ["dotnet", "ConsoleApp1.dll"]
