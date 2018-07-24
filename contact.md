<form action="https://docs.google.com/forms/d/e/1FAIpQLSem00K5ihqoUuMr53pOnxZCFxrhqC87LaxkHI4DxyAFkNh0fg/formResponse" method="post">
    <div class="input-field col s12">
        <i class="material-icons prefix">account_circle</i>
        <input id="icon_prefix" type="text" class="validate" name="entry.460529804" required>
        <label for="icon_prefix">Nome</label>
    </div>
    <div class="input-field col s12">
        <i class="material-icons prefix">comment</i>
        <textarea id="textarea1" class="materialize-textarea" name="entry.1651581134" required></textarea>
        <label for="textarea1">Mensagem</label>
           <div class="background"></div>
            <center><span class="white-text name">{{site.user}}</span></center>
            <center><span class="white-text email">{{site.user_email}}</span></center>
  </div>
    <div class="row center">
        <button class="btn waves-effect waves-light" type="submit" name="submit">Enviar<i class="material-icons right">send</i></button>
        <button class="btn waves-effect waves-light" type="reset" name="reset">Limpar<i class="material-icons right">subject</i></button>
    </div>
</form>
<!--
-->