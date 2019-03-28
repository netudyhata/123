            Console.WriteLine("Таблица температур по Фаренгейту и Цельсию:"); //Вывод строки в консольно окно
            Console.WriteLine("По Фаренгейту    По Цельсию:");

            int lower, upper, step;
            double fahr, cels;

            lower = 0;
            upper = 300;
            step = 20;
            fahr = lower;
            while (fahr <= upper) {
                cels = (5.0 / 9.0) * (fahr - 32.0);
                Console.WriteLine("{0:f}               {1:f}", fahr, cels);
                fahr = fahr + step;
            }
            Console.Write("Для продолжения нажмите любую клавишу"); //Выводится в консольное окно сообщении "Press any key for continue"
            Console.Read();
            Console.ReadKey(true);//Задержка экрана
