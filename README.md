# PHP_Tutorial

<a name="table-of-contents"></a>

## PHP tutorial 目錄 


## Chapter 01 - PHP & MySQL

## Chapter 02 - PHP / MySQL operating environment
[部署](#deploy)

[安裝XAMPP伺服器](#install_XAMPP)

## Chapter 03 - PHP basic
[PHP標籤](#tag)

[PHP語法規定](#provision)


## Chapter 04 - PHP flow control

## Chapter 05 - PHP functions

## Chapter 06 - PHP array

## Chapter 07 - PHP string

## Chapter 08 - PHP date and time

## Chapter 09 - PHP file prosessing

## Chapter 10 - PHP Cookie and session

## Chapter 11 - PHP object-oriented programming

## Chapter 12 - MySQL database management

## Chapter 13 - SQL grammar

## Chapter 14 - PHP and MySQL

## Chapter 15 - Example 1_Message

## Chapter 16 - Example 2_Member system

## Chapter 17 - Example 3_Photo album

## Chapter 18 - shopping cart



<a name="deploy"></a>

## 部署

#### 建置可運作PHP程式的環境，這是非常重要的！

#### PHP 程式必須要在網站伺服器上才能運作，這跟HTML網頁不一樣，HTML網頁可以直接依照網頁檔案來執行瀏覽

#### 建置PHP流程：
> `架設網站伺服器` >  `安裝PHP` > `安裝 MySQL 資料庫`

**[⬆  回到頂端](#table-of-contents)**



<a name="install_XAMPP"></a>

## 安裝XAMPP伺服器、環境設定

#### [下載XAMPP](https://www.apachefriends.org/zh_tw/download.html)

#### 安裝XAMPP

#### 啟動XAMPP面板
> `開啟XAMPP面板` > Strat All
![XAMPP面板](https://github.com/mjjoe1017/PHP_Tutorial/blob/master/images/XAMPP_Control_Panel.png)

#### Apache 伺服器設定
#### PHP 環境設定
#### MySQL 安全設定
#### VScode 安裝設定
**[⬆  回到頂端](#table-of-contents)**


<a name="tag"></a>

## PHP標籤

> PHP 程式碼需要有起始標籤和結束標籤，如下：

```php

    <?php
        //code
    ?>

    <?
        //code
    ?>

```
**[⬆  回到頂端](#table-of-contents)**

<a name="provision"></a>

## PHP 語法規定

### PHP 程式碼英文大小寫代表不同的變數或常數

```php

    // good
    $myVar

    // bed
    $myvar

```

### PHP 結尾分號

```php
    // good
    <?php echo "Hello"; ?>

    // bed
    <?php echo "Hello" ?>
```

### PHP 註解符號

```php
    <?php 
        // 我是註解

        /*
            這裡面的文字
            也是註解
        */
    ?>
```
**[⬆  回到頂端](#table-of-contents)**
