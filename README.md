# imagem-com-opencv.python
abrindo uma imagem no vscode com opencv python 
#importando a biblioteca opencv 
import cv2 as cv

# fotos e o nome da pasta aonde se enconta a imagem minha 
img = cv.imread('fotos/test_image.jpg')

#abrindo a janela com o nome result e a imagem 
cv.imshow('result', img)
#Apos a imagem subir espera aperta qualquer tecla para fechar a janela 
cv.waitKey(0)
