<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>curriculum vittae</title>
</head>
<body>
<main>
<form action="/action_page.php">
    <fieldset>
    <legend> dados pessoais </legend>
    <fieldset>
        <legend>identificação</legend>
        <table>
        <tr style="display: flex; flex-direction: column;">
            <label for="nome">nome:</label>
            <input type="text" id="nome" name="nome">
        </tr>
        <tr>
            <td><label for="nacionalidade">nacionalidade:</label></td>
            <td><label for="cpf">CPF:</label></td>
            <td><label for="passaporte">número do passaporte:</label></td>
        </tr>
        <tr>
            <td>
            <select name="nacionalidade" id="nacionalidade">
                <option value=""></option>
                <option value="brasileira">brasileira</option>
                <option value="estrangeira">estrangeira</option>
            </select>
            </td>
            <td><input type="number" id="cpf" name="cpf"></td>
            <td><input type="number" id="passaporte" name="passaporte"></td>
        </tr>
        </table>
    </fieldset>
    <fieldset>
        <legend>nascimento</legend>
        <table>
        <tr>
            <td><label for="pais">País:</label></td>
            <td><label for="nacionalidade">UF:</label></td>
            <td><label for="cidade">cidade:</label></td>
            <td><label for="data">date:</label></td>
        </tr>
        <tr>
            <td><select name="pais" id="pais">
                <option value=""></option>
                <option value="brasileira">brasil</option>
                <option value="estrangeira">estrangeiro</option>
            </select></td>
            <td>
            <select name="UF" id="UF">
                <option value="1">PA</option>
                <option value="2">AP</option>
                <option value="3">TO</option>
                <option value="4">PE</option>
                <option value="5">AL</option>
                <option value="6">SE</option>
                <option value="7">BA</option>
                <option value="8">RS</option>
            </select></td>
            <td><input type="text" id="cidade" name="cidade"></td>
            <td><input type="date" id="data" name="data"></td>
        </tr>
        </table>

    </fieldset>
    <fieldset>
        <legend>sexo</legend>
        <table>
        <tr>
            <td><input type="radio" name="sexo" id="masculino">
            <label for="masculino">masculino</label></td>
        </tr>
        <tr>
            <td><input type="radio" name="sexo" id="feminino">
            <label for="feminino">feminino</label></td>
        </tr>
        </table>
    </fieldset>
    <fieldset>
        <legend>identidade</legend>
        <table>
        <tr>
            <td><label for="num">número:</label></td>
            <td><label for="orgao">órgão emissor:</label></td>
            <td><label for="estado">UF:</label></td>
            <td><label for="data">data:</label></td>
        </tr>
        <tr>
            <td><input type="number" id="numero"></td>
            <td><input type="text" id="orgao" name="orgao"></td>
            <td>
            <select name="estado" id="estado">
                <option value="1">PA</option>
                <option value="2">AP</option>
                <option value="3">TO</option>
                <option value="4">PE</option>
                <option value="5">AL</option>
                <option value="6">SE</option>
                <option value="7">BA</option>
                <option value="8">RS</option>
            </select>
            </td>
            <td><input type="data" id="data" name="data"></td>
        </tr>
        </table>
    </fieldset>
    <fieldset>
        <legend>filiação</legend>
        <table>
        <tr>
        <td><label name="nomepai">Pai:</label></td>
        <td><label name="nomemae">Mãe:</label></td>
        </tr>
        <tr>
        <td><input type="text" id="pai" name="pai"></td>
        <td><input type="text" id="mae" name="mae"></td>
        </tr>
        </table>
    </fieldset>
    </fieldset>
    </fieldset>
    <fieldset>
    <legend> endereço</legend>
    <fieldset>
        <legend>endereço profissional</legend>
        <table>
        <tr>
        <td><label name="empresa">empresa/instituição:</label></td>
        </tr>
        <tr>
        <td colspan="4"><input type="text" id="empresaname" name="empresaname"></td>
        </tr>
        <tr>
        <td><label name="logradouroname">logradouro:</label></td>
        <td colspan="3"><label for="endereçocasa">endereço:</label></td>
        <td><label for="bairro">bairro:</label></td>
        </tr>
        <tr>
            <td>
            <select name="lname" id="lname">
                <option></option>
                <option>chácara</option>
                <option>condomínio</option>
                <option>rua</option>
            </select></td>
            <td colspan="3"><input type="text" id="endereço" name="endereço"></td>
            <td><input type="text" id="bairro" name="bairro"></td>
        </tr>
        <tr>
            <td><label for="pais2">país:</label></td>
            <td><label for="estado">UF:</label></td>
            <td colspan="2"><label for="cidade">Cidade:</label></td>
            <td><label for="CEPname">CEP:</label></td>
        </tr>
        <tr>
            <td><input type="text" id="pais2" name="pais2"></td>
            <td>
            <select name="estado" id="estado">
                <option></option>
                <option value="1">PA</option>
                <option value="2">AP</option>
                <option value="3">TO</option>
                <option value="4">PE</option>
                <option value="5">AL</option>
                <option value="6">SE</option>
                <option value="7">BA</option>
                <option value="8">RS</option>
            </select></td>
            <td colspan="2"><input type="text" id="cidade" name="cidade"></td>
            <td><input type="number" id="CEP" name="CEP"></td>
        </tr>
        <tr>
            <td><label name="ddd">DDD:</label></td>
            <td><label name="telefone">telefone:</label></td>
            <td><label name="ramal">ramal:</label></td>
            <td><label name="fax">fax:</label></td>
        </tr>
        <tr>
            <td><input type="number" id="ddd"></td>
            <td><input type="number" id="telefone"></td>
            <td><input type="number" id="ramal"></td>
            <td><input type="number" id="fax"></td>
        </tr>
        <tr>
            <td colspan="3"><label for="homepage">homepage pessoal:</label></td>
            <td colspan="4"><label for="email">e-mail:</label></td>
        </tr>
        <tr>
            <td colspan="3"><input type="text" id="homepage" name="homepage"></td>
            <td colspan="4"><input type="text" id="email" name="email"> </td>
        </tr>
        </table>
        
    </fieldset>
    <fieldset>
        <legend>endereço residêncial</legend>

        <table>
        <tr>
            <td><label for="logras">logradouro:</label></td>
            <td colspan="3"><label for="endereco">endereço:</label></td>
            <td><label for="bairro">bairro:</label></td>
        </tr>
        <tr>
            <td>
            <select name="logras" id="logras">
                <option></option>
                <option>Chácara</option>
                <option>Condomínio</option>
                <option>Rua</option>
            </select></td>
            <td colspan="3"><input type="text" id="endereco" name="endereco" ></td>
            <td><input type="text" id="bairro" name="bairro"></td>
        </tr>
        <tr>
            <td><label for="pais">país:</label></td>
            <td><label for="estado">UF:</label></td>
            <td colspan="2"><label for="cidade">cidade:</label></td>
            <td><label for="CEP">CEP:</label></td>
        </tr>
        <tr>
            <td>
            <input type="text" id="moes" name="moes">
            </td>
            <td>
            <select name="estado" id="estado">
                <option></option>
                <option value="1">PA</option>
                <option value="2">AP</option>
                <option value="3">TO</option>
                <option value="4">PE</option>
                <option value="5">AL</option>
                <option value="6">SE</option>
                <option value="7">BA</option>
                <option value="8">RS</option>
            
            </select>
            </td>
            <td colspan="2"> <input type="text" id="cidade" name="cidade"></td>
            <td><input type="number" id="CEP" name="CEP"></td>
        </tr>
        <tr>
            <td><label name="DDD">DDD:</label></td>
            <td><label  name="telefone">telefone:</label></td>
            <td><label  name="ramal">ramal:</label> </td>
            <td><label name="fax">fax:</label></td>
        </tr>
        <tr>
            <td><input type="number" id="DDD"></td>
            <td><input type="number" id="telefone"> </td>
            <td><input type="number" id="ramal"> </td>
            <td><input type="number" id="fax" > </td>
        </tr>
        <tr>
            <td colspan="3"><label name="homepage">homepage pessoal:</label></td>
            <td colspan="4"><label name="email">e-mail:</label></td>
        </tr>
        <tr>
            <td colspan="3"><input type="text" id="homepage"></td>
            <td colspan="4"><input type="text" id="email"  ></td>
        </tr>
        </table>
    </fieldset>
    <fieldset>
        <legend>endereço preferencial</legend>
        <input type="radio" name="endereco" id="residencial">
        <label for="residencial">residencial</label>
        <input type="radio" name="endereco" id="profissional">
        <label for="profissional">profissional</label>
    </fieldset>
    <fieldset>
        <legend>endereço preferencial para correspondência</legend>
        <input type="radio" name="endereco" id="profissional">
        <label for="profissionalc">profissional</label>
        <input type="radio" name="enderecoc" id="residencial">
        <label for="residencial">residencial</label>
    </fieldset>
    </fieldset>
    <fieldset>
    <legend> formação acadêmica ou titulação </legend>
    <fieldset>
        <legend>formação</legend>
        <table>
        <tr>
            <td><label>nível:</label> </td>
            <td><label name="horas">carga horária</label></td>
        </tr>
        <tr>
            <td>
            <select>
                <option value=""></option>
                <option value="1">Graduação</option>
                <option value="2">Especialização</option>
                <option value="3">Doutorado</option>
            </select>
            </td>
            <td><input type="number" id="horas" name="horas"></td>
        </tr>
        </table>
    </fieldset>
    <fieldset>
        <legend>instituição/curso</legend>
        <table>
        <tr>
            <td colspan="2"><label name="instituicao">instituição</label></td>
            <td colspan="2"><label name="curso">nome do curso</label></td>
            <td><label name="status">dtatus do curso:</label></td>
        </tr>
        <tr>
            <td colspan="2"><input type="text" id="instituicao"></td>
            <td colspan="2"><input type="text" id="curso"></td>
            <td><select name="status" id="status">
                <option value=""></option>
                <option value="1">em andamento</option>
                <option value="2">titulo obtido</option>
            </select></td>
        </tr>
        <tr>
            <td><label for="periodo">período:</label></td>
            <td><label for="titulo">título:</label></td>
            <td colspan="2"><label for="oreintador">Nome:</label></td>
        </tr>
        <tr>
            <td><select name="periodo" id="periodo">
                <option value=""></option>
                <option value="1">início</option>
                <option value="2">conclusão</option>
                <option value="3">obtenção do título</option>
            </select></td>
            <td><input type="text" id="titulo" name="titulo"></td>
            <td colspan="3"><input type="text" id="oreintador" name="oreintador"></td>
        </tr>
        <tr>
            <td><label for="bolsa">bolsa:</label></td>
            <td><label for="financeira">entidade financeira</label></td>
        </tr>
        <tr>
            <td> <select name="bolsa" id="bolsa">
                <option value=""></option>
                <option value="1">Sim</option>
                <option value="2">Não</option>
            </select></td>
            <td colspan="1"><input type="text" id="entidade" name="entidade"></td>
        </tr>
        </table>
    </fieldset>
    <fieldset>
        <legend>endereço para correspondência</legend>
        <input type="radio" id="proficional">
        <label name="proficional">Profissional</label>
        <input type="radio" id="residêncial">
        <label name="residêncial">residêncial</label>
    </fieldset>
    </fieldset>
    <fieldset>
    <legend>atuação profissional</legend>
    <fieldset>
        <legend>instituição de trabalho</legend>
        <table>
        <tr>
            <td><label name="empresa">instituição ou empresa</label></td>
            <td><label name="sigla">sigla</label></td>
        </tr>
        <tr>
            <td><input type="text" id="empresa"></td>
            <td><input type="text" id="sigla"></td>
        </tr>
        </table>
    </fieldset>
    <fieldset>
        <legend>atividade:</legend>
        <input type="checkbox" name="1" id="1"><label for="1">conselhos, comissões e consultoria</label><br>
        <input type="checkbox" name="2" id="2"><label for="2">direção e administração</label><br>
    </fieldset>
    <fieldset>
        <legend>vínculo institucional</legend>
        <table>
        <tr>
            <td><label name="bolsa">bolsa:</label></td>
            <td><label name="inicio">início</label></td>
            <td><label name="fim">fim</label></td>
            <td><label name="vinculo">vínculo:</label></td>
            <td><label name="carga">carga Horária</label></td>
        </tr>
        <tr>
            <td><select name="bolsas" id="bolsas">
                <option value=""></option>
                <option value="1">anterior</option>
                <option value="2">atual</option>
            </select></td>
            <td><input type="date" id="inicio" name="inicio"></td>
            <td><input type="date" id="fim" name="fim"></td>
            <td><select name="tipoVei" id="tipoVei">
                <option value=""></option>
                <option value="1">servidor público</option>
                <option value="2">celetista</option>
                <option value="3">outro</option>
            </select></td>
            <td><input type="text" id="carga" name="carga"></td>
        </tr>
        </table>
    </fieldset>
        <input type="submit" id="subimit" name="subimit" value="subimit">
        <input type="reset" id="reset" name="reset" value="reset">
</form>
</main>
</body>
</html>
