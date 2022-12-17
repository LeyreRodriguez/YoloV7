### TRABAJO REALIZADO POR CRISTOBAL Y LEYRE

Para ver el resultado entrar el siguiente directorio runs/detect

Ahi encontraras dos pequeños ejemplos, ya solucionados, en cada una de las carpetas.
Para probar mas opciones, encontraras mas imagenes entrenadas en el directorio data/train/images

Con esas imagenes, escriba lo siguiente en conda y ejecute:
python detect.py --weights yolov7_custom.pt --conf 0.5 --img-size 640 --source ['directorio de imagen o video'] --view-img -no-trace


Para realizar este trabajo, lo primero que hemos hecho ha sido encontrar un data set de imagenes en google, en el cual se mostrasen personas u objetos con gorros de navidad, hemos usado la libreria labelImg para poder producir los documentos labels y asi obtener la posicion de los gorros en cada imagen.
Seguidamente, hemos entrenado la neurona, en 100 epocas con un batch-size de 8. De esta forma, al ejecutar el comando visto en la parte superior de este documento, podemos obtener cualquier gorro de navidad en una imagen o video.

Bibliografia : https://www.youtube.com/watch?v=-QWxJ0j9EY8&t=60s&ab_channel=TheCodingBug