SDK Não Oficial para integração a partir de aplicações PHP com as APIs do EXTRA

## Testes

Antes de iniciar o uso deste componente, verifique as permissões de suas credenciais
utilizando um comando simples (importante: não esqueça de substituir os tokens de exemplo):

```UNIX 
curl -i -H "Accept: application/json" -H "Content-Type: application/json" \
-H "nova-auth-token: ex4mpl0Auth" -H "nova-app-token: ex4mpl0Token" \
"https://sandbox.extra.com.br/api/v1/sellerItems?_offset=0&_limit=2";
```

O comando acima deve lhe entregar uma reposta ``HTTP/1.1 200 OK``




## License

MIT, see LICENSE.


## Links

* [Composer Package](https://packagist.org/packages/gpupo/extra-sdk) on packagist.org