<script lang="ts">
  export const classes: string = "";
</script>

<button on:click class="
  btn btn-primary
  w-full
  my-4
  text-indigo-600
  bg-purple-100
  hover:bg-purple-200
  active:bg-purple-300
  rounded-full
  outline-none
  focus:ring-2
  focus:ring-indigo-600
  active:ring-offset-2
  active:ring-4
  { classes }
  ">
  <slot>Custom Button</slot>
</button>
