# Configurando a Estação de Trabalho

Este repositório contém a estrutura necessária para execução de uma playbook Ansible que irá automatizar a preparação da minha estação de trabalho.

>Aviso:
>
>Esta playbook foi desenvolvida para o Sistema Operacional Ubuntu 20.04. Caso utilize outro SO será necessário adaptar a playbook.

#### **Antes de iniciar**!
>Alerta:
>
>Leia os arquivos ```playbook.yml``` e ```roles/install/tasks/main.yml``` e certifique-se de que entendeu sua execução antes de aplicar em sua máquina.

## Instalação:

1. Instale as ferramentas necessárias para a execução da playbook.
```Shell
sudo apt update && sudo apt install ansible git -y
```

2. Clone este repositório.
```Shell
git clone https://github.com/cleiconde/Desktop.git
```

3. Acesse o diretório **Desktop** e execute a playbook **playbook.yml**.
```Shell
cd Desktop
ansible-playbook -K playbook.yml
```
>Entre com sua senha para efetuar a elevação de privilégio necessária em algumas etapas da instalação


4. Tome um enquanto aguarda sua máquina ficar pronta.
___

## Licence

GNU General Public License v3.0

___

## Autor
Criado por **[Cleidson Conde](https://www.linkedin.com/in/cleidson-conde)**.


