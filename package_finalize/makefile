windows: package_finalize.c
	gcc -static package_finalize.c -L"C:\OpenSSL-Win32\lib\MinGW" -leay32 -o package_finalize.exe

linux: package_finalize.c
	gcc -static package_finalize.c -lcrypto -o package_finalize
