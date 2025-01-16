<template>
  <section>
    <h2>My Friends</h2>
    <ul>
      <li></li>
    </ul>
  </section>
</template>

<script>
export default {
  data() {
    return {
      friends: [
        {
          id: "manuel",
          name: "Manuel",
          phone: "02130130123",
          email: "manuel@gmal.com",
        },
        {
          id: "julia",
          name: "Julia",
          phone: "02130130123",
          email: "julia@gmal.com",
        },
      ],
    };
  },
};
</script>
