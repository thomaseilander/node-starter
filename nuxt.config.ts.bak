const fs = require('fs'); 
const path = require('path');

// https://nuxt.com/docs/api/configuration/nuxt-config
export default defineNuxtConfig({

    server: {
        https: {
            key: fs.readFileSync(path.resolve(__dirname, 'localhost-key.pem')),
            cert: fs.readFileSync(path.resolve(__dirname, 'localhost.pem'))
        }
    }

})

