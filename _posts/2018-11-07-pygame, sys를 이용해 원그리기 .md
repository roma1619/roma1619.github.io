

```python
import pygame, sys
from pygame.locals import *
pygame.init()
screen = pygame.display.set_mode((640, 480))
while 1:
    for event in pygame.event.get():
        if event.type == pygame.QUIT:
            sys.exit()
    screen.fill((255, 255, 255))
    pygame.draw.circle(screen, (0, 255, 0), (100, 200), 20)
    pygame.display.update()
```


    

    ImportErrorTraceback (most recent call last)

    <ipython-input-2-7d9c574d4d41> in <module>()
    ----> 1 import pygame, sys
          2 from pygame.locals import *
          3 pygame.init()
          4 screen = pygame.display.set_mode((640, 480))
          5 while 1:
    

    ImportError: No module named pygame

