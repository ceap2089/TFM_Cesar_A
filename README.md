# TFM
TFM Developed
Hola que tal, gracias por darte el tiempo de revisar este archivo, la presente es para comentarte la estructura de mi TFM titulado. "APPLICATION OF NOISE 2 NOISE DENOISING TECHNIQUES TO ENHANCE THE QUALITY OF IMAGES CORRESPONDING TO MEASUREMENTS FROM WIRELESS TAGS". 

El primer archivo se llama 0_Pruebas_MNIST_BD, aqui podremos ver todas las pruebas explorativas que hice, use del dataset de MNIST debido a que por su dimension de 28x28x1 y en escala de grises me podria dar una metrica parecida a lo que serian mis datos futuros.

El segundo archivo se llama 1_Pruebas_Autoencoder, realiza las prácticas en si, extraigo la base de datos, reordeno el dataset, hago emparejamientos y construyo el autoencoder, al final de cada modelo podras ver los resultados.

El tercer archivo se llama 2_Experimentos_combined_N2C, luego de probar nuestro autoencoder vemos que las mejoras no son suficientes por lo que recurro a construir un dataset probando un modelo clasico como noise - clean, con esta estructura veo los valores subyacentes detras del experimento. Es decir si se hiciera de la forma clásica que valores obtendiramos, para luego comparar contra nuestras técnicas de autoencoders y demás. Para ello uso el dataset de references para ubicar las imagenes mas parecidas mediante el indice de correlacion respecto de las matrices originales.

El cuarto archivo contiene el siguiente experimento, usando imágenes recortadas, trabajando junto los investigadores que llevan este proyecto, Junior Sokodjou me envio un dataset con imagenes recortadas para rehacer mis analisis, para nuestra sorpresa vimos que estos analisis dieron grandes resultados.
