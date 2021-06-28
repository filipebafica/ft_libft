# Libft
An implemenation of libc functions from scratch.

## 🗂 Table of Contents
* [About](#-about)
* [Getting Started](#-getting-started)
* [How to Use](#-how-to-use)
* [Available Functions and Descriptions](#-available-functions-and-descriptions)
* [42 École | 42 São Paulo](#-42-école-42-são-paulo)

## 🧐 About
This is an implementation of libc functions from scratch. This project is part of 42 École/ 42 SP curriculum.\
Topics such as memory allocation, ASCII table, string manipulation, and others were addressed.

## 🏁 Getting Started
A C compiler such as `gcc` or `clang` is needed.

#### ⚙️ Installing
To compile the entire library, clone the repo, and run the commad `make`.
```
$ git clone https://github.com/filipebafica/libft.git
$ cd libft/source
$ make
```
This is going to generate a `libft.a` file that you can compile with your source code.
```
$ gcc my_source.c libft.a
$ ./a.out
```
## 🎈 How to Use
Just call the desired function (go to [Available Functions and Descriptions](#-available-functions-and-descriptions) to see all available functions).
```
ft_split("split-this-for-me-!",'-');
```
#### 👁️‍🗨️ Demonstration
To see a demonstration go to the mains folder, and compile the main of the desired function.
```
$ cd libft/mains
$ gcc ft_split_main.c ../libft/libft.a
$ ./a.out
```
## 📋 Available Functions and Descriptions
| Function  | Prototype | Description |
| ------------- | ------------- | ------------- |
| ft_atoi  | `int	ft_atoi(const char *nptr)` | Converts the initial portion of the string pointed to by nptr to int. Returns the converted value. |
| ft_bzero  | `void	ft_bzero(void *s, size_t n)` | Erases the data in the n bytes of the memory starting at the location pointed to by s, by writing zeroes (bytes containing '\0') to that area. |

## 🏫 42 École | 42 São Paulo
42 École is a network of tech schools spread around the world where anyone can learn how to code for free.\
At 42 there are no teachers or classrooms, each student learn from and work with each other (peer-to-peer learning).\
To see more go to https://www.42.fr/ and https://www.42sp.org.br/.

