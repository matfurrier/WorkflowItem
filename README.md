# 💼 Workflow de Itens APP

## 📝 Sumário
- [Descrição](#descrição)
- [Tecnologias](#tecnologias)
- [Instalação](#instalação)
- [Uso](#uso)
- [Regras e Fluxos do Aplicativo](#regras-e-fluxos-do-aplicativo)
- [Contribuições](#contribuições)
- [Licença](#licença)
- [Contato](#contato)

## 📖 Descrição
Workflow de Itens APP é um aplicativo de gestão desenvolvido para otimizar o processo de solicitação e validação de cadastro de itens. 
Através deste aplicativo, todos os departamentos envolvidos podem colaborar no processo de cadastro, garantindo a precisão das informações e o acompanhamento em tempo real do progresso.

## 🛠 Tecnologias
As seguintes tecnologias foram utilizadas no desenvolvimento deste projeto:
- CSS3
- JavaScript
- React
- Node.js
- Express
- MySQL

## ⚙ Instalação
**Pré-requisitos**
Certifique-se de ter o Node.js e NPM instalados em sua máquina antes de seguir os próximos passos.

**Passo a passo**
Siga os passos abaixo para configurar e executar o projeto localmente:

## 🎮 Uso
Para utilizar o Workflow APP, siga os passos abaixo:

1. Faça login com seu e-mail corporativo e a senha fornecida pela empresa.
![2023-05-30 21_20_57-Data Workflow - De Sangosse App](https://github.com/matfurrier/AppItensDSV1/assets/30526394/84390587-4eb5-470e-95cc-bfd1810b9239)

2. A página principal tem o menu lateral para cadastro de novos itens e listar itens que já foram feitas solicitações de cadastros.
![2023-05-30 21_24_03-Data Workflow - De Sangosse App](https://github.com/matfurrier/AppItensDSV1/assets/30526394/952287da-b447-4022-8c63-15b7a13f524c)

3. Para cadastrar um novo item, os campos são os mesmos que preenchemos atualmente nas solicitações de compras.
![2023-05-30 21_33_53-Data Workflow - De Sangosse App](https://github.com/matfurrier/AppItensDSV1/assets/30526394/b459b4a9-7136-4bf6-991a-611580728896)

4. Quando um novo item for cadastrado, os responsáveis de cada departamento envolvido no processo receberão um e-mail do endereço dsti@desangosse.com.br com os detalhes do item cadastrado.
![2023-05-30 21_34_54-Caixa de Entrada - rosam@desangosse com br - Outlook](https://github.com/matfurrier/AppItensDSV1/assets/30526394/df49bdb8-de81-4b77-bfed-82384a57b99b)

5. Cada colaborador de seu respectivo departamento poderá preencher as informações dos campos que foram encaminhados anteriormente. Todos poderão visualizar qualquer aba, mas, só podem preencher aquela que está relacionada ao seu departamento. Após o preenchimento, sempre clicar no botão SALVAR.
![2023-05-30 21_37_21-Data Workflow - De Sangosse App](https://github.com/matfurrier/AppItensDSV1/assets/30526394/a637deda-ec9f-4c20-b168-ff6a7f641de2)

![2023-05-30 21_39_59-Data Workflow - De Sangosse App](https://github.com/matfurrier/AppItensDSV1/assets/30526394/9cef35c3-f37c-4926-9afc-15a68b1fd973)

![2023-05-30 21_40_57-Data Workflow - De Sangosse App](https://github.com/matfurrier/AppItensDSV1/assets/30526394/a5638d1f-07c9-4bea-86e5-e8ccdff32bfb)

![2023-05-30 21_43_02-Data Workflow - De Sangosse App](https://github.com/matfurrier/AppItensDSV1/assets/30526394/dc476cbb-4b00-4302-a5d4-479125d76919)

6. Os dados podem ser editados enquanto o flag do campo VALIDADO não for marcado. Quando este flag for marcado, todos os campos da aba são desabilitados, não sendo possível modificar mais. Após clicar em VALIDADO, deve clicar no botão SALVAR também.
![2023-05-30 21_44_35-Data Workflow - De Sangosse App](https://github.com/matfurrier/AppItensDSV1/assets/30526394/53cccb3e-5220-4b4f-874c-ec3ca0347d61)

7. Após a inserção e validação de todos departamentos, é possível exportar estes dados para uma planilha de Excel, que posteriormente será utilizada para atualizar no SAP com estes dados.
![2023-05-30 21_43_28-Data Workflow - De Sangosse App](https://github.com/matfurrier/AppItensDSV1/assets/30526394/9903dc47-63ee-4461-84ba-737f838e42e7)

![2023-05-30 21_47_41-dados_completos (3) xlsx - Excel](https://github.com/matfurrier/AppItensDSV1/assets/30526394/fc00d2f8-0d22-4562-8b9a-baa25c72b55d)

8. Quando todos os departamentos validarem os campos, o status do cadastro do item passará a ser “APROVADO”.
![2023-05-30 21_45_52-Data Workflow - De Sangosse App](https://github.com/matfurrier/AppItensDSV1/assets/30526394/f2b98da1-83a7-4d0d-b443-f33ff7cfea9a)

## 💼 Regras e Fluxos do Aplicativo
A eficiência do nosso aplicativo Workflow APP é baseada em algumas regras e fluxos estratégicos. Aqui estão as principais regras que orientam o uso do aplicativo:

- Ao cadastrar um novo item, é necessário enviar para validação dos departamentos envolvidos.
- Os colaboradores só podem editar os campos relacionados ao seu respectivo departamento.
- Os itens só podem ser editados enquanto a opção "VALIDADO" não estiver marcada. Uma vez que esta opção esteja marcada, os campos da aba serão desabilitados e não poderão mais ser modificados.
- Após o item ser validado por todos os departamentos, o status do cadastro do item passará a ser "APROVADO".

## 🤝 Contribuições
Contribuições são sempre bem-vindas!

## 📄 Licença
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para obter detalhes.

## 📬 Contato

Para mais informações ou dúvidas sobre o Workflow de Itens App, entre em contato através do e-mail matfurrier@gmail.com.

Link do Projeto: [https://github.com/matfurrier/AppItensDSV1](https://github.com/matfurrier/AppItensDSV1)

Agradecemos por utilizar o Workflow de Itens App! Esperamos que esta ferramenta seja útil para melhorar a eficiência e colaboração em seu fluxo de trabalho. 🚀
