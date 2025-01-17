hello alfredo and/or twinkle
instructions on updating to stable:

imma be entirely re exporting the files, then the launcher should haddle it. if not:

ensure line 10 is GAME_FILE = "Ballin.pck" and not anything else;
line 69 is if not os.path.exists("Ballin.exe"):    ;
and line 74 is subprocess.run("Ballin.exe")

(make sure it never has the ' as that was the problem with the old version)

