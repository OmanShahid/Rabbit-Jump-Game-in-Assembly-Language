# Rabbit Jump Game in Assembly Language

Rabbit Jump is a 16-bit DOS game written in x86 Assembly language. The game runs in text mode and was developed as a logic-focused low-level programming project.

## Project Files

- main.asm: Source code for the game

## Requirements

- Windows 10 or 11
- NASM (Netwide Assembler)
- DOSBox (or DOSBox-X)

## Build on Windows

1. Open PowerShell in the project folder.
2. Compile the source into a COM executable:

```powershell
nasm -f bin main.asm -o game.com
```

If compilation succeeds, you will get game.com in the same folder.

## Run in DOSBox

1. Start DOSBox.
2. Mount the project directory:

```text
mount c "F:\Django files\course _builder 5\Rabbit-Jump-Game-in-Assembly-Language-"
```

3. Switch to the mounted drive and run the game:

```text
c:
game.com
```

## Controls

- Up Arrow: Jump
- P: Start game (from intro screen)

## Notes

- This is a DOS real-mode Assembly program, so it should be run through DOSBox.
- The code uses BIOS and DOS interrupts and directly writes to VGA text memory.

## Credits

- Oman Shahid
- Syed Aown Raza
