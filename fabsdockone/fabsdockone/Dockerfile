FROM microsoft/aspnetcore
WORKDIR /app
COPY bin/Debug/netcoreapp1.1/publish /app
ENV ASPNETCORE_URLS http://*:58036
EXPOSE 58036
 
ENTRYPOINT /bin/bash -c "dotnet fabsdockone.dll"