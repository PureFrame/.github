<br>
<p align="center">
    <a href="https://github.com/PureFrame" target="_blank">
        <img src="https://raw.githubusercontent.com/PureFrame/.github/main/profile/PureFrame.svg" width="300" alt="PureFrame PHP Framework" />
    </a>
</p>

<h1 align="center">PureFrame PHP Framework</h1>
    <br>
    
Pureframe is a flexible and high-performance PHP framework designed to help you build web applications with ease.
With its intuitive and minimalist architecture, Pureframe offers an elegant and streamlined development experience,
allowing you to focus on crafting top-quality applications. Whether you're building a simple blog or a complex enterprise-grade platform,Pureframe provides a powerful yet lightweight foundation that can help you achieve your goals.

<div align="center">
  
[![Latest Stable Version](http://poser.pugx.org/pureframe/pureframe/v)](https://packagist.org/packages/pureframe/pureframe) 
[![Total Downloads](http://poser.pugx.org/pureframe/pureframe/downloads)](https://packagist.org/packages/pureframe/pureframe) 
[![Latest Unstable Version](http://poser.pugx.org/pureframe/pureframe/v/unstable)](https://packagist.org/packages/pureframe/pureframe) 
[![License](http://poser.pugx.org/pureframe/pureframe/license)](https://packagist.org/packages/pureframe/pureframe) 
[![PHP Version Require](http://poser.pugx.org/pureframe/pureframe/require/php)](https://packagist.org/packages/pureframe/pureframe)
  
</div>

## Features

- PureFrame PHP Framework is a lightweight, object-oriented framework designed to simplify web application development.
- Template system for creating reusable HTML templates and separating presentation from logic
- The framework provides a set of tools and libraries for developers.
- Support for database connections
- Built-in validation library for validating user input
- Error handling and logging system for debugging and monitoring your application

## Getting Started

To get started with Pureframe, simply download the source code and include it in your PHP project.
You can then create controllers, and build your application using the framework.

Here's an example of a controller definition:

```php
<?php
class Sample
{
    use Controller;
    public function index()
    {
        $this->view('index', $data);
    }
}
?>
```
