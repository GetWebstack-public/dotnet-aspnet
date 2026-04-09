FROM mcr.microsoft.com/dotnet/sdk:8.0
WORKDIR /app
COPY dotnet-aspnet.csproj .
RUN dotnet restore
COPY . .
EXPOSE 8080
ENV ASPNETCORE_URLS=http://+:8080
CMD ["dotnet", "watch", "run", "--no-launch-profile"]
