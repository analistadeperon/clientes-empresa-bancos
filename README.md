# clientes-empresa-bancos

<div id="app">
  <div ui-view></div>
</div>

<form>
<img class="img-responsive" src="data:image/jpeg;base64,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">
  <div class="form-group">
    <label for="nome">Nome</label>
    <input type="text" class="form-control" name="nome" id="nome" required>
  </div>

  <div class="form-group">
    <label for="tipo">Tipo</label>
    <select class="form-control" name="tipo" id="tipo">
      <option value="1">Pessoa física</option>
      <option value="2">Pessoa jurídica</option>
    </select>
  </div>

  <div class="form-group">
    <label>Gênero</label>

    <div class="form-check">
      <input class="form-check-input" type="radio" name="genero" id="masculino" [value]="1">
      <label class="form-check-label" for="masculino">Masculino</label>
    </div>
    <div class="form-check">
      <input class="form-check-input" type="radio" name="genero" id="feminino" [value]="2">
      <label class="form-check-label" for="feminino">Feminino</label>
    </div>
  </div>

  <div class="form-group">
    <label for="dataNascimento">Data de nascimento</label>
    <input type="date" class="form-control" name="dataNascimento" id="dataNascimento">
  </div>

  <div class="form-group">
    <label for="observacao">Observação</label>
    <textarea class="form-control" rows="3" name="observacao" id="observacao"></textarea>
  </div>

  <div class="form-check">
    <input class="form-check-input" type="checkbox" name="inativo" id="inativo">
    <label class="form-check-label" for="inativo">Inativo</label>
  </div>

  <input type="submit" class="btn btn-primary mt-4" value="Salvar">
  <a href="#" class="btn btn-secondary mt-4 ml-2">Cancelar</a>

</form>
Apenas letras

<input type="text" required="required" name="text" pattern="[a-z\s]+$" />
Apenas números

<input type="text" required="required" name="numbers" pattern="[0-9]+$" />
Data

<input type="date" required="required" maxlength="10" name="date" pattern="[0-9]{2}\/[0-9]{2}\/[0-9]{4}$" min="2012-01-01" max="2014-02-18" />
Hora

<input type="time" required="required" maxlength="8" name="hour" pattern="[0-9]{2}:[0-9]{2} [0-9]{2}$" />
Campos genéricos de texto

<input type="text" required="required" name="name" />
Telefone

<input type="tel" required="required" maxlength="15" name="phone" pattern="\([0-9]{2}\) [0-9]{4,6}-[0-9]{3,4}$" />
Email

<input type=" confirme email" required="required" class="input-text" name=" confirme email" pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,4}$" />
Confirme Email

<input type="tel" required="required" maxlength="15" name="valor" pattern="([0-9]{1,3}\.)?[0-9]{1,3},[0-9]{2}$" />
Utilizei o type=”tel”, pq em celulares renderiza melhor o teclado.

Input file

<input type="file" name="file" accept="image/*" required="required" />

<div ng-controller="ProdutosController">
  <img class="img-responsive" src="https://balbino.info/wp-content/uploads/2014/12/cadastro-de-produtos.png">
  <h1>Tabela de Preços</h1>

  <!-- cadastro -->
  <div class="panel-heading">Cadastro de Cliente</div>

  <div class="panel-body">
    <form novalidate name="frmCliente" id="formCadastro" role="form">

      <div class="row">


        <div class="form-group col-md-12">
          <label>* Empresa:</label> <input name="inpEmpresa"
                                        maxlength="60" required="required" type="text"
                                        class="form-control" ng-model="cliente.empresa" />
        </div>
        <div class="form-group col-md-12">
          <label>* CNPJ:</label> <input name="inpCnpj" maxlength="16"
                                        required="required" type="text" class="form-control"
                                        ng-model="cliente.cnpj" />
        </div>
        <div class="form-group col-md-6">
          <label>* Cidade:</label> <input name="inpCidade" maxlength="60"
                                        required="required" type="text" class="form-control"
                                        ng-model="cliente.cidade" />
        </div>


        <div class="form-group col-md-12">
          <label>* Endereço:</label> <input name="inpEndereco"
                                        maxlength="60" required="required" type="text"
                                        class="form-control" ng-model="cliente.endereco" />
        </div>

        <div class="form-group col-md-12">
          <label>* E-mail:</label> <input name="inpEmail" maxlength="50"
                                        required="required" type="email" class="form-control"
                                        ng-model="cliente.email" />
        </div>

        <div class="form-group col-md-6">
          <label>* Telefone:</label> <input name="inpTelefone"
                                        maxlength="15" required="required" type="text"
                                        class="form-control" ng-model="cliente.telefone" />
        </div>


        <div class="form-group col-md-6">
          <label>* Contato:</label> <input name="inpContato"
                                        maxlength="30" required="required" type="text"
                                        class="form-control" ng-model="cliente.contato" />
        </div>

        <div class="form-group col-md-12">
          <label>Observação:</label>
          <textarea name="inpObservacao" class="form-control" rows="3"
                                        ng-model="cliente.observacao"></textarea>
        </div>

        <div></div>
      </div>
    </form>
    <div class="pull-right">
      <button type="button" id="btnSalvar" class="btn btn-default"
                                ng-click="salvarClientes()">Salvar</button>
      <!-- ou ng-disabled="frmCliente.inpNome.$invalid"  -->

      <button type="button" class="btn btn-default"
                                ng-click="cancelarAlteracaoClientes(cli)">Cancelar
                                Edição</button>
      <button type="button" id="btnAdCadEquipamento"
                                class="btn btn-default" ng-click="addEquipamento()">
                                <span class="glyphicon glyphicon-plus"></span>
                            </button>
    </div>

  </div>
</div>
</div>

<div ng-controller="equipamentoController">
  <div id="cadEquipInsp" class="col-md-6 ">
    <div class="panel panel-primary">
      <div class="panel-heading">Cadastro de
        Equipamentos / Instrumentos / Produtos</div>

      <div class="panel-body">
        <form novalidate name="frmEquipamento" id="formCadastro" role="form">
          <div class="row">
            <div class="form-group col-md-12">
              <label>Descrição:</label> <input name="inpDescricao"
                                            maxlength="60" required="required" type="text"
                                            class="form-control" ng-model="equipamento.descricao" />
            </div>
            <div class="form-group col-md-6">
              <label>Data da Inspeção:</label> <input
                                            name="inpDataEquipamento" maxlength="16" required="required"
                                            type="date" class="form-control" ng-model="equipamento.dataEquipamento" />
            </div>
            <div class="form-group col-md-6">
              <label>Próxima Inspeção:</label> <input
                                            name="inpProximaInspecao" maxlength="60" required="required"
                                            type="date" class="form-control" ng-model="equipamento.proximaInspecao" />
            </div>
             <div class="form-group col-md-6">
              <label>Data da Entrada:</label> <input
                                            name="inpDataEquipamento" maxlength="16" required="required"
                                            type="date" class="form-control" ng-model="equipamento.dataEquipamento" />
            </div>
             <div class="form-group col-md-6">
              <label>Data da Saída:</label> <input
                                            name="inpDataEquipamento" maxlength="16" required="required"
                                            type="date" class="form-control" ng-model="equipamento.dataEquipamento" />
            </div>
            <!--    <div class="pull-right">
                                    <button type="button" id="btnSalvar" class="btn btn-default"
                                ng-click="salvarEquipamentos()">Salvar</button>
                                 </div> -->
          </div>
        </form>
      </div>
    </div>
  </div>
</div>
<input type="file" name="file" accept="image/*" required="required" />

<div ng-controller="ProdutosController">

  <script type="text/javascript" src="http://code.jquery.com/jquery-2.1.3.min.js"></script>
<script type="text/javascript" src="https://assets.moip.com.br/v2/bank-account-validator.min.js"></script>
<script type="text/javascript">
  $(document).ready(function() {
    $("#validate_bank_account").click(function() {
      Moip.BankAccount.validate({
        bankNumber         : $("#bank_number").val(),
        agencyNumber       : $("#agency_number").val(),
        agencyCheckNumber  : $("#agency_check_number").val(),
        accountNumber      : $("#account_number").val(),
        accountCheckNumber : $("#account_check_number").val(),
        valid: function() {
          alert("Conta bancária válida")
        },
        invalid: function(data) {
          var errors = "Conta bancária inválida: \n";
          for(i in data.errors){
            errors += data.errors[i].description + "-" + data.errors[i].code + ")\n";
          }
          alert(errors);
        }
      });
    });
  });
</script>
<form>
  <img class="img-responsive" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRdi3v4mhg2l1SXTvFv8OCy1kqzJ-rdYk94dtlqk-ApLnOEfRKI5PVE_KJGGjtEWTCMhw&usqp=CAU">
  <select id="bank_number">
    <option value="001">BANCO DO BRASIL S.A.</option>
    <option value="237">BANCO BRADESCO S.A.</option>
    <option value="341">BANCO ITAÚ S.A.</option>
    <option value="104">CAIXA ECONOMICA FEDERAL</option>
    <option value="033">BANCO SANTANDER BANESPA S.A.</option>
    <option value="399">HSBC BANK BRASIL S.A.</option>
    <option value="151">BANCO NOSSA CAIXA S.A.</option>
    <option value="745">BANCO CITIBANK S.A.</option>
    <option value="041">BANCO DO ESTADO DO RIO GRANDE DO SUL S.A.</option>
  </select>

  <input id="agency_number" placeholder="Agência" type="text"/>
  <input id="agency_check_number" placeholder="Dígito da agência" type="text" />
  <input id="account_number" placeholder="Conta corrente" type="text" />
  <input id="account_check_number" placeholder="Dígito da conta corrente" type="text" />

  <input type="button" value="Validar" id="validate_bank_account" />
  <textarea placeholder="Deixe sua opnião"></textarea>

  <input type="submit" class="enviar" onclick="Enviar();" value="Enviar" />
</form>
</body>
</html>

