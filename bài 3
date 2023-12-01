using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Bài_3_update
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.OutputEncoding = Encoding.UTF8;
            do
            {
                int n;
                bool lyLuan = false;
                do
                {
                    Console.Write("Nhập số nguyên n: ");
                    if (int.TryParse(Console.ReadLine(), out n) && n >= 0)
                    {
                        lyLuan = true;
                    }
                    else
                    {
                        Console.ForegroundColor = ConsoleColor.Red;

                        Console.WriteLine("Giá trị n không hợp lệ. Vui lòng nhập lại.");

                        Console.ResetColor();
                    }
                } while (!lyLuan);
                for (int i = 1; i < n; i += 2)
                {
                    Console.ForegroundColor = ConsoleColor.Green;
                    Console.Write(i + " ");
                    Console.ResetColor();
                }
                lyLuan = false;
                Console.WriteLine();
                Console.Write("Bạn có muốn tiếp tục không? (Y/N): ");

                string choice = Console.ReadLine();

                if (choice.ToUpper() != "Y")
                {
                    break;
                }

                Console.WriteLine();
            } while (true);
        }
    }
}
