# Cambio Perfil PumaMóvil

Esta rama contiene los cambios de la sección del perfil del usuario de la aplicación PumaMóvil.

## Cambios

Se implementó el uso de la cámara del dispositivo para tomar fotos y establecerla como imagen de perfil.

Se implementó la integración del [SDK de Facebook](https://developers.facebook.com/docs/android/) para obtener datos del perfil público del usuario.

## Bibliotecas

Se utilizaron bibliotecas third-party cómo:

-[Picasso](https://square.github.io/picasso/).

-[CircleImageView](https://github.com/hdodenhof/CircleImageView).

## Uso

Para obtener los datos del perfil público de Facebook se hace uso del [API GRAPH](https://developers.facebook.com/docs/graph-api). Al terminar la obtención de datos del perfil público del usuario, estos datos se guardan en la clase UsuarioFacebook, para posteriormente usarlos. 

Se hace uso de la biblioteca third-party Picasso para insertar el URI que se obtiene de la imagen del perfil del usuario en un CircleImageView, el uso de la biblioteca CircleImageView tiene como fin dar un formato circular a la foto del perfil.
