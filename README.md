# Projeto-LoRaCare
Projeto voltado para monitoramento da saúde de pessoas que moram na zona rural, utilizando módulo LoRa e sensores biomédicos


# bom depois deu perceber que deu erro de merge, eu dei um git pull  pelo vscode resolveu o problema de merge, aceitando as alterações, e depois dei um  git push

![imagem](./erro_merge.png)


# Exercicio de regressao: A Lara mudou o trecho  
 1 Apenas um número: statistics.stdev exige >=2 dados -> deve falhar e mencionar "two data points".
 def test_stats_cmd_um_numero_quebra_stdev():
   res = runner.invoke(app, ["stats-cmd", "42"])
   
     assert res.exit_code != 0
     assert "two data points" in (res.output + str(res.exception)).lower()

    Ela alterou o sinal de diferente para igual.
 logo em seguida eu arrumei o erro para passar tudo, foi gerado o relatorio de de teste via HTML

![imagem](./imagem1.png)
![imagem](./imagem2.png)
