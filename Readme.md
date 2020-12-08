CSService - папка, где находятся файлы данного проекта. Класс Acts содержит методы шифрования, дешифрования, архивации и разархивации файла. Класс General реализует методы из Acts и создаёт новую папку. Класс Parser реализует классы XMLParser и JsonParser для работы с XML и JSON, а также содержит интерфейс IParser. Оба класса реализуют виртуальный метод Parse() для парсинга файлов .json и .xml расширений соответственно. 
Имеются конфигурационные файлы appsettings.json и config.xml. 
Файл шифруется и архивируется. затем переносится в другую папку, где теперь дешифровывается и разархивируется.