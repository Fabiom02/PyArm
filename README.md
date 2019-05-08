## VERY EASY ROBOTIC ARM - VERA
---
Conjunto e bibliotecas e softwares em *Python* e *C++* para controle de braços robóticos baseados na plataforma *Arduino*.

Desenvolvido por membros e voluntários do [Capítulo Estudantil IEEE RAS UFCG](https://www.facebook.com/rasufcg/)

---
**vision-sys.py** - Python 3.6

Software para identificação e localização de objetos.

Módulos necessários:

 - OpenCV -  (`pip install opencv-python`)
 - MatplotLib - (`pip install matplotlib`)
 - Pillow - (`pip install Pillow`)
 - Numpy - (`pip install numpy`)
 - pySerial - (`pip install pyserial`)

 Caso ao tentar executar vision-sys.py receba o erro:
 
 `ModuleNotFoundError: No module named 'tkinter'`

Execute o seginte comando no terminal:

`sudo apt-get install python3-tk`