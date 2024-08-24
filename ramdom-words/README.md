# Publicar un Package (NPM)

## Install

En caso de estar solo local:

        sudo npm link
        pwd -> copiamos la ruta
        npm install -g [ruta]
        random-words -> ejecuta 

            Después verificamos que el comando de inicio sirva -> el comando lo encontramos en:

                "bin": {
                "random-words": "bin/global.js"   -> el comando es -> random-words
                }

En caso de estar publicado:

        npm install -g random-words
        random-words -> ejecuta