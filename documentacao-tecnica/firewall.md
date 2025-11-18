# Firewall

#### Como criar regras de entrada e saída no Firewall ? <a href="#como-criar-regras-de-entrada-e-saida-no-firewall" id="como-criar-regras-de-entrada-e-saida-no-firewall"></a>

Esse processo é realizado para que um computador possa ser acessado por outro na rede ou para permitir que um computador acesse outro na rede.

Os passos abaixo deverão ser realizados para criar regras de entrada e saída para as portas 1433 e 1666, mas os processos devem ser feitos separadamente para cada regra e porta.

Abrir o **painel de controle**, alterar exibição para **ícones grandes** e clicar em **Windows Defender Firewall**.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FSYbUEcnrglGEGOOjgWX4%252FFirewall%2520painel%2520de%2520controle.png%3Falt%3Dmedia%26token%3Dc592a666-221b-4a3f-85bc-7602716ada05\&width=768\&dpr=4\&quality=100\&sign=970e9024\&sv=2)

Na próxima tela, clicar em **Configurações avançadas.**

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F65z5IChfNMTpNPrai7un%252FFirewall%2520configuracoes%2520avancadas.png%3Falt%3Dmedia%26token%3D3f847585-ba90-469d-8b25-9b10b8b3682f\&width=768\&dpr=4\&quality=100\&sign=ded0bd01\&sv=2)

Na tela que será aberta, clicar em **regras de entrada** ou **regras de saída** e logo após clicar em **nova regra**.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F7H0H6SFxgTkrQ0LJUi52%252FFirewall%2520nova%2520regra.png%3Falt%3Dmedia%26token%3Da5d9603b-23d1-4b6b-a5b2-0cd349788a5b\&width=768\&dpr=4\&quality=100\&sign=a6b6f4d8\&sv=2)

Na aba **tipo de regra**, selecionar a opção **Porta** e clicar em **avançar.**

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FzmTo2XN1FT91Uw2jSWEv%252FFirewall%2520porta.png%3Falt%3Dmedia%26token%3Da0b6577b-9dc9-4a3b-8faf-71143f43d930\&width=768\&dpr=4\&quality=100\&sign=d2c57907\&sv=2)

Em **protocolos e portas**, selecionar **TCP, portas locais específicas** e inserir a porta **1433** ou **1666** e clicar em **avançar.**

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FxE25rhs99Zb16YdjCN6L%252FFirewall%2520porta%25201433.png%3Falt%3Dmedia%26token%3Df2665264-f083-42e8-a918-9ceaa483e721\&width=768\&dpr=4\&quality=100\&sign=d756433d\&sv=2)![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FBsRtoGma8qXSiEFchopb%252FFirewall%2520porta%25201666.png%3Falt%3Dmedia%26token%3D2fa6db6d-4bec-421a-8121-ac6b21e42de6\&width=768\&dpr=4\&quality=100\&sign=a0a7e683\&sv=2)

Em **protocolos e portas**, selecionar **TCP, portas locais específicas** e inserir a porta **1433** ou **1666** e clicar em **avançar.**

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FxE25rhs99Zb16YdjCN6L%252FFirewall%2520porta%25201433.png%3Falt%3Dmedia%26token%3Df2665264-f083-42e8-a918-9ceaa483e721\&width=768\&dpr=4\&quality=100\&sign=d756433d\&sv=2)![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FBsRtoGma8qXSiEFchopb%252FFirewall%2520porta%25201666.png%3Falt%3Dmedia%26token%3D2fa6db6d-4bec-421a-8121-ac6b21e42de6\&width=768\&dpr=4\&quality=100\&sign=a0a7e683\&sv=2)

Na aba ação, selecionar a opção **permitir conexão** e clicar em **avançar.**

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FglHF3rMpQPKECffTZGyH%252FFirewall%2520permitir%2520conexao.png%3Falt%3Dmedia%26token%3Dd6bc04c2-7049-47f8-b0f0-32a47c20d465\&width=768\&dpr=4\&quality=100\&sign=4612e26d\&sv=2)

Em **perfil,** selecionar todas as opções **(domínio, particular e público)** e clicar em **avançar.**

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FiXYXuVPqhAy0ke69HsEN%252FFirewall%2520perfil.png%3Falt%3Dmedia%26token%3D84d6a475-81d8-4abb-9341-5c3b1f0f5e0f\&width=768\&dpr=4\&quality=100\&sign=a5cf7213\&sv=2)

Na aba **nome**, inserir o nome da regra e clicar em **concluir.**

O nome padrão das regras utilizadas pela DMASTER são **PortaSql1433** ou **PortaSql1666.**

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FBNHqVgzVmEp51Go7Do7x%252FFirewall%2520nome%2520porta%25201433.png%3Falt%3Dmedia%26token%3D0cb24b1b-30c3-426e-83dc-858e4440bb88\&width=768\&dpr=4\&quality=100\&sign=f35ac9d7\&sv=2)![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FSwLosGSzFkSWjSZIkGJy%252FFirewall%2520nome%2520porta%25201666.png%3Falt%3Dmedia%26token%3D9d6b81c1-060c-48e9-a4dc-5ec2801ae691\&width=768\&dpr=4\&quality=100\&sign=efd91623\&sv=2)

Após os processo acima, as regras do firewall foram criadas.
