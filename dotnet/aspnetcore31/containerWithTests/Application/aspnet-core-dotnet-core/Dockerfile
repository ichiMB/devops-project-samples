FROM mcr.microsoft.com/dotnet/core/aspnet:3.1-buster-slim
WORKDIR /app

# Copy the published web app
COPY /aspnet-core-dotnet-core/ /app

# Run command
ENTRYPOINT ["dotnet", "aspnet-core-dotnet-core.dll"]
