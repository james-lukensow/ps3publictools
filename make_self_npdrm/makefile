windows: make_self.c
	gcc -static make_self.c -I"C:\Program Files (x86)\GnuWin32\include" -L"C:\OpenSSL-Win32\lib\MinGW" -lgmp -leay32 "C:\Program Files (x86)\GnuWin32\bin\zlib1.dll" -o make_self_npdrm.exe

linux: make_self.c
	gcc -static make_self.c -lgmp -lcrypto -lz -o make_self_npdrm
