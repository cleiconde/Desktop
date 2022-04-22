# Configurando a Estação de Trabalho

Este repositório contém a estrutura necessária para execução de uma playbook Ansible que irá automatizar a preparação da minha estação de trabalho.

>Aviso:
>
>Esta playbook foi desenvolvida para o Sistema Operacional Ubuntu **[20.04]()**. Caso utilize outro SO será necessário adaptar a playbook.

#### **Antes de iniciar**!
>Alerta:
>
>Certifique-se de que entendeu a execução desta playbook antes de aplicar em sua máquina (prefira usar uma máquina virtual para testes).

## Instalação:

1. Instale as ferramentas necessárias para a execução da playbook.
```Shell
sudo apt update
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible git -y
ansible-galaxy collection install community.general
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


___

## Licence

GNU General Public License v3.0

___

## Autor
Criado por **[Cleidson Conde](https://www.linkedin.com/in/cleidson-conde)**.


