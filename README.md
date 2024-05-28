# matyo-17
![GitHub last commit](https://img.shields.io/github/last-commit/matyo-17/matyo-17?label=last%20updated)

```php
class AboutMe {
    protected string $base = "malaysia";
    protected string $first_name = "Filson";
    protected string $last_name = "Teo";
    protected string $email = "filsonteo@gmail.com";
    protected string $description = "a software developer";
    protected string $website = "https://matyo-17.github.io/";
    protected array $fav_programming_lang = ["php", "python", "javascript"];
    protected array $fields_interested = [
        "software development", "artificial intelligence", "machine learning",
        "robotics", "image processing",
    ];
    protected array $open_sources = [
        "https://github.com/matyo-17/mysql-backup",
        "https://github.com/matyo-17/fotmob-sdk",
    ];

    public function introduce(): string {
        $string = "<p>Name: ".$this->get_name()."</p>";
        $string .= "<p>Overview: ".$this->description."</p>";
        $string .= "<p>Based in: ".ucfirst($this->base)."</p>";
        $string .= "<p>Website: ".$this->get_website()."</p>";
        $string .= "<p>Email: ".$this->email."</p>";
        $string .= "<p>Fields interested: ".$this->get_fields_interested()."</p>";
        $string .= "<p>Favourite programming language: ".$this->get_fav_programming_lang()."</p>";
        $string .= "<p>Open sources: ".$this->get_open_sources()."<br>";
        return $string;
    }

    private function get_name(): string {
        return $this->first_name." ".$this->last_name;
    }

    private function get_website(): string {
        return "<a href='".$this->website."'>".$this->website."</a>";
    }

    private function get_fav_programming_lang(): string {
        $string = "";
        foreach ($this->fav_programming_lang as $lang) {
            $string .= $lang.", ";
        }
        return substr($string, 0, -2);
    }

    private function get_fields_interested(): string {
        $string = "<ul>";
        foreach ($this->fields_interested as $field) {
            $string .= "<li>".$field."</li>";
        }
        $string .= "</ul>";
        return $string;
    }

    private function get_open_sources(): string {
        $string = "<ul>";
        foreach ($this->open_sources as $link) {
            $string .= "<li><a href='".$link."'>".$link."</a></li>";
        }
        $string .= "</ul>";
        return $string;
    }
}

$about_me = new AboutMe();
echo $about_me->introduce();
```

### 🔨 Language & Tools

<a href="https://www.php.net/">
    <img height="25" width="25" src="icons/php.svg">
</a>&nbsp;
<a href="https://www.python.org/">
    <img height="25" width="25" src="icons/python.svg">
</a>&nbsp;
<a href="https://www.cprogramming.com/">
    <img height="25" width="25" src="icons/c.svg">
</a>&nbsp;
<a href="https://www.java.com/en/">
    <img height="25" width="25" src="icons/java.svg">
</a>
&nbsp;
<a href="https://laravel.com/">
    <img height="25" width="25" src="icons/laravel.svg">
</a>&nbsp;
<a href="https://www.djangoproject.com/">
    <img height="25" width="25" src="icons/django.svg">
</a>&nbsp;
<a href="https://fastapi.tiangolo.com/">
    <img height="25" width="25" src="icons/fastapi.svg">
</a>&nbsp;
<a href="https://pandas.pydata.org/">
    <img height="25" width="25" src="icons/pandas.svg">
</a>
&nbsp;
<a href="https://www.mysql.com/">
    <img height="25" width="25" src="icons/mysql.svg">
</a>&nbsp;
<a href="https://www.sqlite.org/">
    <img height="25" width="25" src="icons/sqlite.svg">
</a>&nbsp;
<a href="https://redis.io/">
    <img height="25" width="25" src="icons/redis.svg">
</a>&nbsp;
<a href="https://www.javascript.com/">
    <img height="25" width="25" src="icons/javascript.svg">
</a>&nbsp;
<a href="https://html.spec.whatwg.org/multipage/">
    <img height="25" width="25" src="icons/html.svg">
</a>&nbsp;
<a href="https://www.w3.org/Style/CSS/Overview.en.html">
    <img height="25" width="25" src="icons/css.svg">
</a>&nbsp;
<a href="https://nginx.org/en/">
    <img height="25" width="25" src="icons/nginx.svg">
</a>&nbsp;
<a href="https://httpd.apache.org/">
    <img height="25" width="25" src="icons/apache.svg">
</a>&nbsp;
<a href="https://www.docker.com/">
<img height="25" width="25" src="icons/docker.svg">
</a>&nbsp;
<a href="https://git-scm.com/">
    <img height="25" width="25" src="icons/git.svg">
</a>&nbsp;
<a href="https://github.com/">
    <img height="25" width="25" src="icons/github.svg">
</a>&nbsp;
<a href="https://about.gitlab.com/">
<img height="25" width="25" src="icons/gitlab.svg">
</a>&nbsp;
<a href="https://code.visualstudio.com/">
    <img height="25" width="25" src="icons/vscode.svg">
</a>&nbsp;
<a href="https://www.postman.com/">
    <img height="25" width="25" src="icons/postman.svg">
</a>&nbsp;
<a href="https://www.mathworks.com/products/matlab.html">
    <img height="25" width="25" src="icons/matlab.svg">
</a>&nbsp;
<a href="https://www.haskell.org/">
    <img height="25" width="25" src="icons/haskell.svg">
</a>&nbsp;

---
Made with ❤️ by [@matyo-17](https://github.com/matyo-17)

<!--
**matyo-17/matyo-17** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
