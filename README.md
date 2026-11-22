<p align="center">
  <img src="icone.png" alt="Sossego, um guarda-sol branco sobre fundo azul" width="120">
</p>

<h1 align="center">Sossego</h1>

<p align="center">
  <strong>Receitas, despesas e lembretes do mês, sem pressa.</strong><br>
  Um programa para Windows com poucas telas, letra grande e nenhum anúncio.
</p>

<p align="center">
  <a href="https://github.com/PedroRigolon/sossego-releases/releases/latest"><strong>⬇ Baixar a versão mais recente</strong></a>
</p>

---

## O que é

O Sossego mostra, mês a mês, o dinheiro que entra, as contas a pagar e os lembretes, em telas simples e com letra
fácil de ler.

- **Dinheiro:** o que entrou (receitas) e o que ainda falta pagar (despesas), com o total de cada mês.
- **Agenda:** um calendário com o que vence em cada dia: contas, receitas e lembretes.
- **Avisos:** no menu, o que está atrasado e o que vence hoje e nos próximos 3 dias.
- **Despesas que se repetem** todo mês (aluguel, luz, internet) aparecem sozinhas, com o último valor.
- **Funciona sem internet:** mostra o que tinha da última vez, guarda o que você fizer e envia sozinho quando a
  internet volta.
- Sem anúncios e sem senha nova para decorar: a entrada é com a conta Google.

## Como instalar

Precisa de **Windows 10 ou 11 (64 bits)**, uns 400 MB livres e internet na primeira vez, para entrar com a conta Google.

1. Abra a [página da versão mais recente](https://github.com/PedroRigolon/sossego-releases/releases/latest) e, em
   **Assets**, clique em `Sossego-…-setup.exe` para baixar.
2. Dê dois cliques no arquivo baixado.
3. **O Windows vai mostrar um aviso azul: "O Windows protegeu seu computador".** Isso é normal. O instalador ainda não
   tem assinatura digital (que é paga), e o Windows desconfia de programas novos. Clique em **Mais informações** e
   depois em **Executar assim mesmo**.
4. A instalação é de um clique, **não pede senha de administrador** e leva poucos segundos. Ela cria um atalho na Área
   de Trabalho e no Menu Iniciar e já abre o Sossego.
5. Na primeira vez, clique em **Entrar com Google**. O navegador abre uma vez para você escolher a conta e, depois, o
   Sossego volta sozinho.

> Baixe o instalador **somente desta página**. Se um site qualquer oferecer o "Sossego", não é este.

## Atualizações

Você não precisa baixar de novo. O Sossego procura uma versão nova quando abre e de tempos em tempos, baixa nos
bastidores e **instala quando você fecha o programa**. Na próxima vez que abrir, já é a versão nova. Não aparece janela,
pergunta nem aviso.

Para ver qual versão está instalada: **Configurações do Windows › Aplicativos › Sossego**.

## Seus dados

- Ficam guardados na sua conta, na nuvem do Google (Firebase), e só quem entrou com a sua conta consegue ler.
  Também fica uma cópia no computador, para funcionar sem internet.
- O Sossego não tem anúncios nem rastreadores.
- O banco de dados é administrado por quem mantém o programa, que tem acesso técnico ao painel dele.
- **Sair da conta** (no menu do programa) apaga a cópia que ficou no computador. Os dados continuam na sua conta.
- **Desinstalar** não apaga o seu login nem os seus dados: se instalar de novo e entrar com a mesma conta, tudo volta.

## Perguntas frequentes

**O Windows disse que o aplicativo pode ser perigoso. Posso instalar?**
Pode, se você baixou desta página. O aviso aparece porque o instalador não tem a assinatura digital paga que a
Microsoft reconhece. Veja o passo 3 de "Como instalar".

**O antivírus bloqueou o instalador.**
Programas sem assinatura às vezes são marcados por engano. Confirme que baixou desta página e libere o arquivo no
antivírus.

**Como desinstalo?**
Configurações do Windows › Aplicativos › Sossego › Desinstalar.

**Perdi meus lançamentos depois de reinstalar.**
Eles ficam na sua conta. Entre com a **mesma** conta Google que usava antes.

**Posso usar em dois computadores?**
Pode, com a mesma conta Google; os dados acompanham. Evite mexer nos dois ao mesmo tempo.

**Aparece "Falha no login".**
Confira a internet e tente de novo. O navegador precisa abrir para escolher a conta.

**Aparece "Sem internet" no alto da tela.**
O Sossego continua funcionando. O que você fizer fica guardado e é enviado sozinho quando a internet voltar; uma
faixa verde avisa quantos lançamentos foram enviados.

**Abro o Sossego duas vezes e só aparece uma janela.**
É de propósito: o programa só abre uma janela por vez, para não bagunçar os dados guardados no computador.

**Funciona no Mac, no Linux ou no celular?**
Não. Só Windows 10 e 11 de 64 bits.

## Para quem mantém este repositório

Este repositório guarda **somente os instaladores** (o código-fonte fica em um repositório privado). O programa instalado
lê daqui para se atualizar, então cada versão (em **Releases**) precisa ter, sem mudar o nome:

| Arquivo | Para que serve |
| --- | --- |
| `Sossego-X.Y.Z-setup.exe` | o instalador |
| `Sossego-X.Y.Z-setup.exe.blockmap` | permite baixar só o que mudou nas atualizações |
| `latest.yml` | diz ao programa qual é a versão mais nova e confere o arquivo baixado |

- O número da versão tem de **subir** a cada release; é assim que o programa percebe que há novidade.
- Versões marcadas como **pre-release** ou salvas como **rascunho** são ignoradas pelo programa.
- Não apague nem renomeie arquivos de uma release publicada.

## Aviso

Programa de uso pessoal, oferecido como está, sem garantias.
