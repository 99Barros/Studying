# FESA-ALGORTIMOS1


            /* -------------------------------------------
             Usando o IndexOf
            */
            int primeiro;
            String nome = "Ana Maria";
            //             012345678

            //buscar letra "a"
            Console.WriteLine("primeiro 'a': {0}", nome.IndexOf('a')); // devolve 2

            Console.WriteLine("ultimo 'a': {0}", nome.LastIndexOf('a')); //devolve 8

            primeiro = nome.IndexOf('a');

            Console.WriteLine("do meio 'a': {0}", nome.IndexOf('a', primeiro+1)); //devolve 5


            Console.ReadKey();
