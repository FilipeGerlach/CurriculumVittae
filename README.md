<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curriculum Vittae</title>
</head>
<body>
    <fieldset >
        <legend>
            Dados Pessoais
        </legend>
        <fieldset>
            <legend>Identificação</legend>

            Nome Completo: <input type="text"><br>
            Nacionalidade: <input type="radio" name="Nacionalidade" value="braileiro" >braileiro 
            <input type="radio" name="Nacionalidade" value="estrangeira" id="">Nacionalidade <br>
            CPF: <input type="text" maxlength="11"> <br>
            Numero do Passaporte: <input type="text" maxlength="11">
        </fieldset>
        <fieldset>
            <legend>Data de Nascimento</legend>

            Data: <input type="date"><br>
            País: 
            <select name="" id="">
                    <option value="Brasil">Brasil</option>
                    <option value="Japão">Japão</option>
                    <option value="EUA">EUA</option>
                    <option value="Inglaterra">Inglaterra</option>
                    <option value="Australia">Australia</option>
                    <option value="China">China</option>
            </select>
            <br>
            UF: 
            <select name="" id="">
                    <option value="Paraná">Paraná</option>
                    <option value="Pará">Pará</option>
                    <option value="Amazonas">Amazonas</option>
                    <option value="São Paulo">São Paulo</option>
                    <option value="Rio de Janeiro">Rio de Janeiro</option>
                    <option value="Bahia">Bahia</option>
            </select>
            <br>
            Cidade: <input type="text" required>
        </fieldset>
        <fieldset>
            <legend>Sexo</legend>

            
            sexo: <input type="radio" name="sexo" value="masculino" >masculino
            <input type="radio" name="sexo" value="feminino" id="">feminino <br>
        </fieldset>
        <fieldset>
            <legend>Identidade</legend>

            Numero: <input type="text"><br>
            Órgão Emissor:<input type="text"><br>
            UF:<select name="" id="">
                    <option value="Paraná">Paraná</option>
                    <option value="Pará">Pará</option>
                    <option value="Amazonas">Amazonas</option>
                    <option value="São Paulo">São Paulo</option>
                    <option value="Rio de Janeiro">Rio de Janeiro</option>
                    <option value="Bahia">Bahia</option>
                </select>
            <br>
            Data: <input type="date" required>
        </fieldset>
        <fieldset>
            <legend>Filiação</legend>

            Nome Pai: <input type="text"><br>
            Nome Mãe: <input type="text"><br>
        </fieldset>
    </fieldset>
    
</body>
</html>
