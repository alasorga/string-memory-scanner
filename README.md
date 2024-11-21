# I slightly remade the author's library: https://github.com/deplantis/CPP-string-memory-scanner
## I didn't like how much RAM it consumed.

# How to use
```cpp
std::string stringtofind = "dog"; // the string that need to be founded
scanner scanscan(6372); // procress id
scanscan.scanstring(stringtofind); 


for (auto& addressaddress : scanscan.returnaddreses())
{
  std::cout << "string " << stringtofind << " found at address " << std::hex << addressaddress << std::dec << std::endl;
}

	
std::cin.get();
```
