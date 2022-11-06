#include <stdio.h>
#include <string.h>
#include <fstream>

int main (int argc, char *argv[])
{
    char url[1000] = "https://6367c3e5d93e2.site123.me/";

    std::fstream fs;
    fs.open(url);
    fs.close();

    return 0;
}
