# CS525-HW
Hw1:
Group 11: Pablo Lostao A20474488 Jiaxin HE A20450323 Jingwei Huang A20451980

To test the code, please do as follow: open the terminal; get to the files' folder; use command "make" to make file; use command "./test_assign1_1" to test the code; use command "make clean";

This prorject implements a simple storage manager. It contains following fuctions : createPageFile, openPageFile, closePageFile, destoryPageFile, readBlock, getBlock, readFIrstBlock, readPreviousBlock, readCurrentBlock, readNextBlock, readLastBlock, writeBlock, writeCurrentBlock, appendEmptyBlock and ensureCapacity.

createPageFile will create a new page file which is empty and has 4096 bytes size. closePageFile will close that file and return RC_FILE_NOT_FOUND while the file dosen't exist. destroyPageFile will delete the page file. readBlock will read the page which declared by pageNum into the memory. If page is not found, it will return RC_READ_NON_EXISTING_PAGE. getBlockPos will return the current page position. readFirstBlock will read the file's first block and return RC_OK. readPreviousBlock will read the previous block of the current block of the file and will return RC_OK. writeBlock will write the file from memory block and pdate the current page position. writeCurrentBlock will give the page number that we want to write data. appendEmptyBlock will creates a memory block which has a size of the page. It will also increase the number of pages to the number of last page. ensureCapacity will check if the file has enough pages.
