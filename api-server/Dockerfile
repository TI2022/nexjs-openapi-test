FROM --platform=linux/amd64 node:22-alpine

# Install required dependencies for Prisma
RUN apk add --no-cache openssl

RUN npm i -g @nestjs/cli

WORKDIR /backend

COPY . .

# RUN npm install --non-interactive --frozen-lockfile

# RUN npm run build

# CMD ["npm", "run", "start"]