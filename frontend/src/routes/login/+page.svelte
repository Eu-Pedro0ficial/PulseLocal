
<script>
  import Input from "$lib/components/Input.svelte";
  import Button from "$lib/components/Button.svelte";


</script>

<main class="max-w-screen max-h-screen flex flex-col items-center gap-6">
  <section class="w-full flex justify-center items-center">
    <h1 class="text-3xl font-bold">Pulse Local</h1>
  </section>

  <section class="flex flex-col w-[50%] justify-center items-center gap-6">
    <form class="flex flex-col gap-4 w-full items-center" action="">
      <Input type="email" placeholder="E-mail" />
      <Input type="password" placeholder="Senha" />

      <Button text="Entrar"/>
    </form>

    <a href="/registry">Não tenho conta</a>
  </section>
</main>

