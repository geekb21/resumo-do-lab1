# Criando uma Máquina virtual no Azure.

### 1. **Acessar o Portal do Azure**
   - Acesse o portal do Azure através do navegador, usando suas credenciais.

### 2. **Criar um novo recurso**
   - No painel principal, clique em "Criar um recurso" no canto superior esquerdo e selecione a opção "Máquina Virtual" ou pesquise por ela na barra de pesquisa.

### 3. **Configurar a máquina virtual**
   - **Nome e região:** Defina o nome da VM, a região onde ela será implantada (por exemplo, Leste dos EUA) e escolha a conta de assinatura apropriada.
   - **Sistema Operacional:** Escolha a imagem do sistema operacional (Windows, Linux, etc.).
   - **Tamanho da VM:** Selecione o tamanho (número de CPUs, memória RAM) da VM com base em suas necessidades de recursos.

### 4. **Configurar discos e armazenamento**
   - Escolha o tipo de disco (SSD ou HDD) e defina o tamanho do armazenamento que será utilizado.

### 5. **Configurar rede**
   - **Rede virtual:** Escolha ou crie uma rede virtual (VNet) e sub-rede para conectar a VM.
   - **Endereço IP público:** Decida se deseja um endereço IP público ou privado para a VM.

### 6. **Revisar e criar**
   - Revise todas as configurações para garantir que estão corretas e clique em "Criar". O Azure irá provisionar a VM, o que pode levar alguns minutos.

### 7. **Acessar a máquina virtual**
   - Após a criação, você poderá acessar a VM pelo endereço IP público usando RDP (para Windows) ou SSH (para Linux), dependendo da configuração de autenticação definida.
