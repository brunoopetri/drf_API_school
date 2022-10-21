![image](https://user-images.githubusercontent.com/98756562/195112085-8c041d43-392e-4748-af2a-932db8b048b2.png)


# Django Rest Framework

Atualmente não basta criar um sistema. Este sistema tem que ser comunicável, ou seja, deve ser possível de usar este sistema em comunicação com outros sistemas.

A forma mais comum de comunicação entre sistemas é através de serviços web mais conhecidos atualmente como APIs .

Uma biblioteca muito poderosa para construções de APIs: o Django Rest Framework, ou DRF para os intímos!

Com o DRF é possível combinar Python e Django de uma forma flexível para desenvolver APIs web.

### Instalando e configurando o DRF

* Partindo comando do ambiente virtual com o Django instalado, vamos instalar o DRF com o seguinte no terminal:

  ``pip install djangorestframework``

* Após isso vamos criar nosso projeto através dos comandos:

  ``django-admin startproject setup .``

  ``python manage.py startapp escola``

* Com o comando abaixo vamos realizar as migrações no banco de dados:
  
  ``python manage.py makemigration``
  
  ``python manage.py migrate``
  
  

 
### **[API renderiza esses dados para Json](https://drf-schoolenrollment-api.herokuapp.com/)**

O JSON (JavaScript Object Notation) não é um protocolo de transporte de informações como o HTTP. Ele é somente uma forma bem leve de representação e troca de informações. O JSON é somente uma forma de representar informações que precisam ser transportadas de um lado para outro - entre um cliente e um servidor.
 
  * **Visualização raiz básica padrão para DefaultRouter**


![api root](https://user-images.githubusercontent.com/98756562/195928250-5c4000fa-a3fb-4fa0-9a16-f155682f5d6d.png)


* **Lista de alunos**


![alunos List](https://user-images.githubusercontent.com/98756562/195928822-8343c0df-7c7b-4c21-9d43-b04a36ae9af9.png)


* **Lista de cursos**

![cursos list](https://user-images.githubusercontent.com/98756562/195929028-32380904-9209-4685-9d6c-1fd5f6f1cf44.png)


* **Lista de matrículas**

![matriculas list](https://user-images.githubusercontent.com/98756562/195929119-4c790d2b-b026-4f29-8482-e3ef63247002.png)



### **[API em Python com Django Rest Framework](https://drf-schoolenrollment-api.herokuapp.com/admin/login/?next=/admin/)**

* **Site de Administração do Django**

![administacao django](https://user-images.githubusercontent.com/98756562/195940075-c3d4c4d2-fc22-4b68-87f4-b868c9e15814.png)


![administracao site](https://user-images.githubusercontent.com/98756562/195944790-c9d42a7b-508f-41af-a667-66386e99b77a.png)



* **Cadastro Alunos - Cursos - Matrículas**

![cursos](https://user-images.githubusercontent.com/98756562/195944903-9af6f3d6-2056-4313-a94f-13a55ceaf6c6.png)

