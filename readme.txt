// Setup
1. Extract EFI.zip
2. Place the files in a fat32 partition. USB or DISK


// Compile

1. unzip gnu-efi.zip
2. Open the sln file with visual studio.
3. Build the solution
4. place the generated file "X64\release or debug\grubx64_real.efi YOUR DRIVER LETTER EXAMPLE coping grubx64_real.efi to D:\EFI\boot\

// Run

1. Reboot pc
2. Press f2 or something. // Booting into uefi bios
3. Enable secure boot: Standard | Enable | on.
4. Change bootorder to your fat32 partition and make sure windows is number 2.
