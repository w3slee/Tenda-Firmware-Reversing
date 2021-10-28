# Reverse Engineering The Tenda N301 Router

The router's processor is runnning MIPS

running strings on the decompiled binary and searching for MIPS confirms this.

<code>
stings decompressed/tenda.bin | grep mips
</code>



<code> binwalk -C decompressed/tenda.bin </code>



