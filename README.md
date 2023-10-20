# Sklauncher-Arch

## Installing and Running

### Step 1
  Download the universal .jar file from the [SKLauncher Official Site](https://skmedix.pl/downloads)

### Step 2
  Make the file executable ( after renaming and moving to the desiried locatuon if you want to )
  ```
   chmod +x <filename>.jar
```

### Step 3
   Execute the file
   ```
   sudo java -jar <filename>.jar
```

## To create a desktop Shortcut / Exec file

### Step 1
  Create a  script named SKLauncher.sh using nano sklauncher.sh
  ```
#!/bin/bash
java -jar <filename>.jar
```
### Step 2
``` chmod +x sklauncher.sh```

### Step 3
Create a Desktop Iccon

```nano sklauncher.desktop```

```
[Desktop Entry]
Type=Application
Name=SKLauncher
Exec=<path/name>.sh
Icon=<path/name>.png
Terminal=false
Caegories=Game;
```

### Step 4
Move it to local directory.
Usually it's
```~/.local/share/applications/```

### It's done ig...

