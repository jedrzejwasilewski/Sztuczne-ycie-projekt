# Sztuczne-ycie-projekt
#projekt na progamowanie
import pygame
import random
import math
pygame.init()

screen=pygame.display.set_mode((800, 600))


pygame.display.set_caption("Sztuczne życko")

running=True
while running:
    for event in pygame.event.get():
        if event.type==pygame.QUIT:
            running=False
    screen.fill((0,128,0))

    pygame.display.update()
