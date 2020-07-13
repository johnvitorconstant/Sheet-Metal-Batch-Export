# Sheet-Metal-Batch-Export
 How to use:
 https://youtu.be/8d8kBv7TcXs
 
Problemas Conhecidos

Se ocorrer algum erro durante a execução da macro, clique em “debug/depurar”
1) Erro 438 “Set FolhaAtual = swApp.ActiveDoc.GetCurrentSheet” – Verifique a linha de cima do código, o caminho “C:\ProgramData\SOLIDWORKS\SOLIDWORKS 2018\templates\Deasenho.drwdot” deve conter um caminho de template de desenho válido
2) Erro “dict itens” biblioteca não encontrada – Verifique se a biblioteca Microsoft está habilitada no seu computador. Para isso, na tela do vba, vá em Ferramentas > Referências e verifique se essas referencias estão ativas