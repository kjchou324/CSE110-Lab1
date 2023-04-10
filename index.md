# User Page

## Intro
Hello, ny name is Kian, and I am currently a second year mathematics-computer science major at UCSD. Some programming languages I have used in the past and are familiar with include:
- Java
- JavaScript
- Python
- C++
- C
- [MatLab](index.md#MatLab)

I have worked with a little bit of JavaScript in the past, mainly for personal projects. One JavaScript framework that I have some experience with is React (more specifically ReactNative). My personal GitHub can be found [HERE](https://github.com/kianchou), although most of my projects are private since I don't like sharing bad code. Also go check out the [README](README.md).

Some things outside of computer science that I enjoy are video games and golf. Here is an image of the most recent course I played

![Tierra Rejada Golf Course](https://thegolfwire.com/wp-content/uploads/2018/09/tierrarejada.jpg)

## Classes
Here is my list of CSE classes that I have taken, in order from **most** difficult to **least** difficult (my own opinion):
1. 30
2. 105
3. 101
4. 21
5. 20
6. 12
7. 100
8. 15L
9. 11

Also, we can't forget about THE quote (that I may or may not have followed with this assingment):
> Start Early, Start Often

## MatLab
Since everyone loves MatLab, heres a snippet of matlab code that I used for another class.
```matlab
% Computes product of AB, and counts the number of floating point operations
function [prod,flop] = multiplyMatrix(A,B)
    % Matrix A Size: m x n
    % Matrix B Size: n x p
    m = size(A,1);
    n = size(A,2);
    p = size(B,2);
    
    prod = zeros(m,p);
    flop = 0;

    for i = 1:m
        for j = 1:p
            a_i = A(i,:);
            b_j = B(:,j);
            prod_ij = 0;
            for k = 1:n
                % compute inner product of a_i and b_j
                prod_ij = prod_ij + a_i(k)*b_j(k);
                flop = flop + 2;
            end
            prod(i,j) = prod_ij;
        end
    end
end
```

## Task Lis
Here is a list of the Markdown elements my page includes (totally not to just fufill this requirement)
- [X] Headings
- [X] Styling text
- [X] Quoting text
- [X] Quoting code
- [X] External Links
- [X] Section links
- [X] Relative links
- [X] Ordered and Unordered Lists
- [X] Task lists