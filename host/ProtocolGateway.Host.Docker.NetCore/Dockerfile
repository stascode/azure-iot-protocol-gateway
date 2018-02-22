# build runtime image
FROM microsoft/dotnet:2-runtime 
WORKDIR /app
COPY out/ /app
ENTRYPOINT ["dotnet", "ProtocolGateway.Host.Console.dll"]