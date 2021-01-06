# template-url

Inogda nuzhno prisozdanii temy Wordpress
poluchit' adres direktorii vnuti JS-fayla.

Dlya etogo vnutri index.php (ili dr. Glavnogo fayla)
vnutri tega golova dobv"avit' sl.konstruktsiyu
Sometimes you need to create a Wordpress theme
get the address of the directory inside the JS file.

    <script type="text/javascript">
        var templateUrl = '<?= get_bloginfo("template_url"); ?>';
    </script>

Иногда нужно присоздании темы Wordpress 
получить адрес корневой директории внути JS-файла.

Для этого внутри index.php(или др. главного файла)
внутри тега head добвъавить сл.конструкцию

    <script type="text/javascript">
        var templateUrl = '<?= get_bloginfo("template_url"); ?>';
    </script>

