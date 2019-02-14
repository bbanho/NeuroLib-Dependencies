# Instalação
Para executar a instalação automática basta copiar o conteúdo deste diretório para onde deseja instalar. A seguir, execute diretamente o script install.sh.

```bash
$ git clone https://github.com/bbanho/NeuroLibDependencies.git
$ cd NeuroLibDependencies
$ yes | sh install.sh
```

Ou apenas

```bash
$ git clone https://github.com/bbanho/NeuroLibDependencies.git; cd NeuroLibDependencies; yes | sh install.sh
```

## Etc
```bash
Para verificação de erros
$ ./install.sh > log
```
O script se encarregará de realizar as instalações necessárias.

Para o teste de instalação deve-se fornecer as imagens e executar os scripts

```bash
$ python3 NeuroLib.py
$ python3 NeuroFrame.py
```
### TODO

* Observar licença de software proprietário
	* https://www.baslerweb.com/en/service/pylon-eula/

