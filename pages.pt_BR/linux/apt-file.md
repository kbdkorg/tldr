# apt-file

> Buscador de arquivos nos pacotes APT, incluindo os não instalados.
> Mais informações: <https://manned.org/apt-file.1>.

- Atualiza as informações dos pacotes a partir de todos os repositórios remotos:

`sudo apt update`

- Busca por pacotes que contêm o arquivo ou caminho especificado:

`apt-file search {{nome_do_pacote_ou_caminho}}`

- Lista o conteúdo de um pacote específico:

`apt-file list {{nome_do_pacote}}`
