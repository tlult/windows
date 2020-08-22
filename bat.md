##### Run python script every 6 sec

    :loop
    cd "C:\Users\..\..\Scripts"
    call activate.bat
    cd ..
    python main.py
    
    timeout /t 6 /nobreak
    goto loop
