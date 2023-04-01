# RenLua
Interpreter for making and porting RenPy games to PSP.
The interpreter works according to the following principle. It searches for all (.rpy) scripts in the game folder, then loads and checks them in advance on labels, menu, ifs. After that, the interpreter jumps to the start label and starts interpreting the RenPy code. In order to interpret python code, a FakePython library was created to read python statements in (.rpy) scripts.
At the moment, you can output text, images, perform some image manipulation, play sounds, and even create your own mini-game inside the novel using imagemap function. Therefore, I hope that this interpreter will be actively used in the PSP Homebrew Community and the list of visual novels on the PSP will be constantly expanding. That's it.
