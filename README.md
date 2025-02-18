# PHPImagick
Você precisa instalar ou ativar a extensão Imagick



📌 Como Instalar a Extensão Imagick no PHP (Windows)

✅ Passo 1: Verificar a versão do PHP
Antes de instalar o Imagick, certifique-se da versão do PHP instalada no seu sistema:
	
	php -v
	Você pode baixar a versão correspondente do Imagick em:
	🔗 Download Imagick



✅ Passo 2: Verificar a arquitetura do PHP (32 ou 64 bits)
Para saber se seu PHP é 32 bits (x86) ou 64 bits (x64), execute:


	php -i | find "Architecture"
	Se o resultado for x86, seu PHP é 32 bits.
	Se for x64, seu PHP é 64 bits.


✅ Passo 3: Baixar a versão correta do Imagick
Agora, escolha o arquivo correto para sua versão do PHP.

	🔹 Detalhes importantes na escolha do arquivo:

	Versão do PHP (Ex: 8.1, 8.2...)
	Arquitetura: x86 (32 bits) ou x64 (64 bits)
	Tipo de thread: TS (Thread Safe) ou NTS (Non-Thread Safe)
	📥 Exemplo:
	Se você estiver usando PHP 8.1 x64 TS, baixe:
	php_imagick-3.7.0-8.1-ts-vs16-x64.zip

Baixe o arquivo em:
🔗 Download Imagick






✅ Passo 4: Instalar a extensão Imagick
	1️⃣ Extraia o conteúdo do arquivo .zip baixado.
	2️⃣ Copie o arquivo php_imagick.dll para a pasta de extensões do PHP:


	C:\xampp\php\ext



✅ Passo 5: Mover os arquivos .dll necessários
	Além do php_imagick.dll, copie todos os outros arquivos .dll que vieram 	no .zip para os diretórios abaixo:

	📂 Cole em:

	C:\xampp\apache\bin
	C:\Windows\System32



✅ Passo 6: Habilitar o Imagick no PHP
	1️⃣ Edite o arquivo php.ini (geralmente localizado em C:\xampp\php\php.ini).
	2️⃣ Adicione a seguinte linha no final do arquivo:


	extension=php_imagick.dll
	3️⃣ Salve o arquivo e reinicie o Apache.



✅ Passo 7: Verificar se a instalação foi bem-sucedida
Abra o Prompt de Comando como administrador e execute:

	php -m | find "imagick"

	Se o Imagick estiver instalado corretamente, o terminal exibirá:


	imagick
🎉 Pronto! Agora o Imagick está instalado e funcionando no PHP do seu Windows. 🚀
