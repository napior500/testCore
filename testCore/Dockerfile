FROM mcr.microsoft.com/dotnet/core/sdk:3.0 AS build-env
WORKDIR /app

ENV counter=10

COPY . ./

CMD [ "sh","-c","dotnet run ${counter}" ]