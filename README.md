# Backend - Strapi application

Backend server for events app.

1. clone repo using SHH. Note - do not use http because it will be deprecated very soon.

```
// ssh
git clone git@github.com:ChimCollective/events-strapi-v2-backend.git

```

2. Don't forget to install those dependencies! Install with yarn or npm

```
// install dependencies with yarn
yarn

// OR install dependencies with npm
npm i

```

3. To work on this project. </br>
   From the 'main' branch -> create 'your feature branch'

```
git checkout -b yourName_yourFeature
```

### Run the Server

```bash
npm run develop
# or
yarn develop
```

Open [http://localhost:1337/admin](http://localhost:1337/admin) to access the CMS

### Using Cloudinary

Create a .env file and add your Cloudinary info for images

```
CLOUDINARY_NAME = "xxxx"
CLOUDINARY_KEY = "xxxx"
CLOUDINARY_SECRET = "xxxx"
```
