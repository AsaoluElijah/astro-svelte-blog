<script>
  export let blog;
</script>

<div
  class="bg-gray-80 outline outline-2 outline-offset-2 outline-gray-300 rounded-lg m-h-64 p-3 py-5 transform hover:translate-y-2 hover:shadow-xl transition duration-300"
>
  <h5 class="text-2xl mt-3 font-bold capitalize leading-none">
    {blog.title}
  </h5>

  <p class="mt-6 capitalize leading-7">
    {blog.body.length > 100 ? blog.body.substring(0, 110) + "..." : blog.body}
  </p>
</div>
