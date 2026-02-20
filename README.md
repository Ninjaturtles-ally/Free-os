print("############################################")
print("#           Welcome to DoodleOS            #")
print("############################################")

# ================================
#   DOODLE OS - BOOT SCREEN
# ================================

print(r"""
    ⠀⠀⠀⠀⠀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⠀⠀⠀⠀⠀
    ⠀⠀⢀⣴⣿⠿⠛⠉⠉⠉⠛⠻⠿⣿⣦⡀⠀⠀⠀
    ⠀⣰⣿⠟⠁⠀⠀⠀⠀⠀⠀⠀⠀⠈⠻⣿⣆⠀
   ⢠⣿⠏⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠹⣿⡄
   ⣿⡏⠀⠀⠀⠀⠀ DOODLE OS⠀⠀⠀⠀ ⠀⢹⣿
   ⢿⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⡿
    ⠹⣿⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⣿⠏
      ⠙⢿⣦⣀⠀⠀⠀⠀⠀⠀⠀⣀⣴⡿⠋
         ⠙⠿⣿⣶⣶⣶⣶⣿⠿⠋
""")

print("Booting Doodle OS...")
print("Loading system modules...")
print("Ready!\n")

# ================================
#   MAIN SYSTEM START
# ================================

print("Starting DoodleOS...")
print("Loading kernel...")
print("Loading UI modules...")
print("Setting up environment...\n")
print("[ OK ] Kernel Loaded")
print("[ OK ] UI Initialized")
print("[ OK ] System Ready\n")

print("Hello, user!")
print("This is the first boot of DoodleOS.")
print("Built with passion and creativity!\n")

print("Type 'help' to see commands.\n")

while True:

    cmd = input("DoodleOS> ")

    if cmd == "help":
        print("\nCommands:")
        print(" help  - show help")
        print(" about - show info")
        print(" pez   - secret command")
        print(" exit  - shutdown\n")
        print(" ball  - secret command")
        print(" guess - secret command")

    elif cmd == "exit":
        print("\nShutting down...")
        break

    elif cmd == "about":
        print("\nDoodleOS v1.3 by Neno\n")

    elif cmd == "pez":
        print("\nPEZ SYSTEM:")
        print(" นายก็ชอบหรอ 🌸\n")

    elif cmd == "ball":
        print("\nBALL SYSTEM:")
        print(" ระวังหน่อย \n")

    elif cmd == "guess":
        print("\nguess system:")
        print(" ยังไม่เสร็จ \n")

    else:
        print("Unknown command. Type 'help'\n")
