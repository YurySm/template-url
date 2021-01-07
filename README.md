# template-url

Sometimes you need to get the root directory address inside the JS file when you create a Wordpress theme.

To do this, inside index.php (or other main file) inside the head tag, add the next construct

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

