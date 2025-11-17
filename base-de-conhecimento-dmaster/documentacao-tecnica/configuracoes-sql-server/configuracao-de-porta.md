# Configuração de porta

Para realizar configuração de porta no SQL Server é preciso seguir alguns passos, que serão citados e explicados a seguir.

Acessar o **SQL Server Configuration Manager.**

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F8btDNt5dp7GjXUw2F1gk%252Fsql%2520server%2520configuration.jpg%3Falt%3Dmedia%26token%3D561723ec-f9af-40f3-a8d0-80d14b0c833f\&width=768\&dpr=4\&quality=100\&sign=6f6c0a92\&sv=2)

Na tela de configuração, expandir a opção **Configuração de Rede do SQL Server** e clicar na opção **Protocolos para MSSQLSERVER**.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fx3kmWeik7vy42e1qJY3d%252Fconfig%2520porta.jpg%3Falt%3Dmedia%26token%3Dff500522-7643-4750-ae70-4aa98df37d4f\&width=768\&dpr=4\&quality=100\&sign=9012bcf2\&sv=2)

Ao lado, clicar com o botão direito em **TCP/IP** e clicar em **Propriedades.**

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FLgv8g3T7HYelF8yCeu9C%252Fconfig%2520porta%25201.jpg%3Falt%3Dmedia%26token%3De58513d7-b336-494e-a7ea-d626f1698ba8\&width=768\&dpr=4\&quality=100\&sign=16e595bb\&sv=2)

Clicar na aba **Endereços IP,** ir até a opção **IPAll,** inserir a porta **1666** no campo **Porta TCP** e clicar **Aplicar** em **OK.**

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FakpXsKFGcLJb1rx2FwI6%252Fconfig%2520porta%25201666.jpg%3Falt%3Dmedia%26token%3Db8a51cc0-7895-4f14-979a-a9f9a2d1126d\&width=768\&dpr=4\&quality=100\&sign=401251e2\&sv=2)

Para concluir a alteração, é preciso reiniciar o serviço do SQL. Para isso, é preciso clicar na opção **Serviços do SQL Server** e ao lado clicar com botão direito em **SQL Server(MSSQLSERVER)** e clicar em **Reiniciar**.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fuw6xoeXRadtmqp4Hpj9I%252Freinciar%2520servico.jpg%3Falt%3Dmedia%26token%3D46f64a55-8765-4d42-a0c1-89c37baebd61\&width=768\&dpr=4\&quality=100\&sign=7fd4ef04\&sv=2)
