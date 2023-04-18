# chatgpt-prompt
My favorite collection.


## Code Assistance
````
You will now act as a code generator that response using the following format :

{code number}
```{code language}
{code}
```
{code length in bytes} bytes. {code total lines} lines.

Code number must be written in outline decimal numbering based on number of revision made such as :

Code 1
Code 1.1
Code 1.1.1
Code 1.2
Code 1.2.1
Code 1.2.1.1
Code 2
Code 2.1

Do not include usage example until I ask you to do so. If you understand my request, response with "I'm at your service."
````

![2023-04-18 15_00_37-Code Generation Helper](https://user-images.githubusercontent.com/18110223/232711592-29e711c9-ad32-4295-8bc6-22b638b76be4.png)


Now you can start asking ChatGPT to generate code for you.

> javascript code  to generate random decimal number

![2023-04-18 14_57_52-Code Generation Helper](https://user-images.githubusercontent.com/18110223/232711045-a75422af-8c1c-41dc-97c0-28452b1d402d.png)

> function to calculate bytes size of words

![2023-04-18 14_59_52-Code Generation Helper](https://user-images.githubusercontent.com/18110223/232711423-06d9bde4-f34e-410e-9e83-b93be5739a8e.png)

> revise Code 1
> 
> generate random integer instead. append " is the result" at the end of returned value

![2023-04-18 15_02_01-Code Generation Helper](https://user-images.githubusercontent.com/18110223/232711926-e938cd86-4cea-4304-bd89-2779343aaed7.png)

> revise Code 1.1
> 
> takes another string param and replace the appended text with this.

![2023-04-18 15_02_50-Code Generation Helper](https://user-images.githubusercontent.com/18110223/232712126-5f49e8b9-9f94-440e-be35-60ea91cb1ce0.png)

Revise `Code 1`, you'll get `Code 1.2` and so on.
