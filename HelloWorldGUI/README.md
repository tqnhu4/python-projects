#Framework	Tkinter

#1. Manual Test
python hello_world_gui.py

#2. Auto Test
python -m unittest test_hello_world_gui.py

#3. Install
sudo apt update
sudo apt install python3-tk -y

#4. Docker
RUN apt-get update && apt-get install -y python3-tk

#5. Check
python3 -c "import tkinter; print('Tkinter is available')"
