<script>
  import Input from "$lib/components/Input.svelte";
  import Button from "$lib/components/Button.svelte";
</script>

<main class="max-w-screen max-h-screen flex flex-col items-center gap-6">
  <section class="m-2">
    <div class="w-40 h-40 bg-gray-400 rounded-full"></div>
  </section>

  <section class="flex flex-col w-[50%] justify-center items-center gap-6">
    <form class="flex flex-col gap-4 w-full items-center" action="">
      <Input type="text" placeholder="Primeiro nome"/>
      <Input type="text" placeholder="Segundo nome"/>
      <Input type="email" placeholder="E-mail"/>
      <Input type="password" placeholder="Senha"/>
      <Input type="password" placeholder="Confirmação de senha"/>
      <Input type="date" placeholder="Data de nascimento"/>

      <Button text="Cadastrar"/>
    </form>
  </section>
</main>
