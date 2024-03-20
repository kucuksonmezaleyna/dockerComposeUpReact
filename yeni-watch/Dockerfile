# Node.js tabanlı bir imajı temel al
FROM node:14

# Çalışma dizinini /app olarak ayarla
WORKDIR /app

# package.json ve package-lock.json dosyalarını kopyala
COPY package*.json ./

# Bağımlılıkları yükle
RUN npm install

# Tüm proje dosyalarını kopyala
COPY . .

# Uygulamayı başlat
CMD ["npm", "start"]