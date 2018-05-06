# 동원
## Footer

## USING :NTH-CHILD


* :nth-child(8)

```
li:nth-child(8) span {
    background-color: #298EB2;
    box-shadow: -3px -3px 10px rgba(0, 0, 0, 0.4), inset 0 0 10px black;
}
````

![Alt text](/images/img-1.png)

> GENERIC CHILD RANGES

* nth-child(n+4):nth-child(-n+8)

```
li:nth-child(n+4):nth-child(-n+8) span {
    background-color: #298EB2;
    box-shadow: inset -3px -3px 10px rgba(0, 0, 0, 0.4), 0 0 10px black;
}
```
![Alt text](/images/img-2.png)

* nth-child(n+2):nth-child(odd):nth-child(-n+9)
```
li:nth-child(n+2):nth-child(odd):nth-child(-n+9) span {
    background-color: #298EB2;
    box-shadow: inset -3px -3px 10px rgba(0, 0, 0, 0.4), 0 0 10px black;
}
```
![Alt text](/images/img-3.png)
## USING THE :NTH-OF-TYPE
>:NTH-OF-TYPE

* :nth-of-type(3)
```
/* these are represented with blue circles */
span:nth-of-type(3) {
    background-color: #298EB2;
    box-shadow: inset -3px -3px 10px rgba(0, 0, 0, 0.4), 0 0 10px black;
}

/* these are represented with orange squares */
div:nth-of-type(4) {
    background-color: #E17149:
    box-shadow: inset -3px -3px 10px rgba(0, 0, 0, 0.4), 0 0 10px black; 
}
```
![Alt text](/images/img-4.png)