# MathRoots
пример использования библиотеки

using System;
using MathRoot;

namespace Program 
{
    class MainClass 
    {
        public static void Main()
        {
            Root root = new Root(27 , 3);
            Console.Write("Итоговое: " + RootTools.ComputeRoot(root, 15));
        }
    }
}
