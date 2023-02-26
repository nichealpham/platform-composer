<h1 align="center">
  <a href="https://gramme.io/cassand"><img src="https://nichealpham.github.io/Cassandra-project/public/images/startup.png" alt="Markdownify" width="160"></a>
  <br>
  <span style="font-size:120px">Platform Composer</span>
  <br>
  <br>
  <a href="https://www.youtube.com/watch?v=DjqP67_SnsY&t=335s">
  <img src="https://github.com/nichealpham/his-composer/blob/main/public/banner.jpg?raw=true" alt="Image Logo">
  </a>
  <br/>

# How To Use

## 1. Run using docker compose 🌈

A pre-built version of this platform is ready to use with docker compose:

### Check the ip adress of your system

```bash
$ ipconfig
$ ifconfig
```

### Then, replace the IP address inside .env file

It is best to setup DNS for each of these endpoints.

- VUE_APP_API_URL: Contains the IP or DNS of API server
- VUE_APP_ERP_URL: Contains the IP or DNS of CRM website
- VUE_APP_SHOP_URL: Contains the IP or DNS of Ecommerce website

```bash
VUE_APP_MSSQL_DB_HOST=172.31.117.133
VUE_APP_MSSQL_DB_USER=sa
VUE_APP_MSSQL_DB_PASSWORD=Admin123
VUE_APP_ACCESS_TOKEN_ENCRYPTION_KEY=sandrasoft@2021_2023
VUE_APP_API_URL=http://172.31.117.133:2001
VUE_APP_ERP_URL=http://172.31.117.133:3001
VUE_APP_SHOP_URL=http://172.31.117.133:3002

```

## Run the app

```bash
$ docker-compose up -d
```

Then navigate to the following URL:

1. [http://localhost:3001](http://localhost:3001): ERP platform
2. [http://localhost:3002](http://localhost:3002): Minishop
3. [http://localhost:2001](http://localhost:2001): API Swagger

# Credits

This software is made by these technologies:

- [.NET Core](https://dotnet.microsoft.com/)
- [SQL Server](https://www.microsoft.com/en-us/sql-server)
- [Vue.js](https://vuejs.org/)

# Support

💪 We are looking for business collaboration to extend the impact of this product and to validate its functionalities for international standards. Please contact us for any opportunities 🔥

<h3>⭐ Contact Information</h3>
Name:  Nicheal Pham<br/>
Technical Solution Architect at Sandrasoft, Co.Ltd. <br/>
Email: nichealpham@gmail.com<br/>
Linkedin: https://www.linkedin.com/in/nichealpham/<br/>
Phone: +84-914-118-896

---

# License

GNU Public 3.0

---

With 💙 from [@Nicheal Pham](https://github.com/nichealpham)
