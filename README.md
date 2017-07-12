# OrderBook2
Real-time order book processing supporting (A)dd, (D)elete and (M)odify operation.
Program written in C++11. Program reads in input (see sample below), and output to standard output/console.

Input format:

Add - Symbol|Op|Side|OrderId|OrderSize|Price:
ABB|A|S|343453|5800|21.1300

Delete - Symbol|Op|OrderId:
ABB|D|343453

Modify - Symbol|M|orderId|newSize|newPrice:
MSFT|M|123453|8000|70.0000

File description:

orderBook2.cpp: C++11 program, can be compiled and executed.

orderBook2.exe: Compiled executable on Windows 10.

orderBookInput.txt: sample order input file for this program. Should be in the same directory as executable/source code.

orderOutput.txt: Console captured output of the program using sample order input file.
