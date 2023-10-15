# Multitenancy

# COMO FAZER!!
1. [inserir os valores nas colunas da tabela pelo terminal](#opcao1)
2. [Criando uma Resource](#opcao2)
3. [Opção 3](#opcao3)
4. [Opção 4](#opcao4)

...

<a name="opcao1"></a>
## inserir os valores nas colunas da tabela pelo terminal

1. Abra o terminal no diretório raiz do seu projeto Laravel.
2. Inicie o Tinker executando o seguinte comando:
```sh
php artisan tinker
   ```
3. Crie uma nova instância do modelo
```sh
$user = new \App\Models\User;
$user->id = '1'; 
$user->name = 'Nome do Usuário';
$user->password = 'senha';
$user->phone = 'phone';

```
4. Salve a instância do modelo no banco de dados usando o método 'save()' :
```sh
$user->save();
```


<a name="opcao2"></a>
## Criando uma Resource

```sh
php artisan make:filament-resource NameResource

```



<a name="opcao3"></a>
## Opção 3

Aqui está a explicação para a Opção 3.



<a name="opcao4"></a>
## Opção 4

Aqui está a explicação para a Opção 4.




