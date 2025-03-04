<template>
  <ProfileInfo
    photo="/imagens/photo.jpg"
    title="Samuel Miranda"
    subtitle="@samuel_2rm"
    headline="Data & Analytics | AI | Software Engineer"
  />

  <main class="max-w-xs mx-auto">
    <ButtonAction
    link="https://www.linkedin.com/in/samuel-miranda-71b545192/"
    icon="👨🏽‍💻"
    text="LinkedIn"
    />

    <ButtonAction
    link="https://wa.me/5561996943025"
    icon="📞"
    text="WhatsApp"
    />

    <ButtonAction
    link="https://www.instagram.com/samuel_2rm/"
    icon="📷"
    text="Instagram"
    />

    <ButtonAction
    link="https://github.com/SamuelEngMek"
    icon="🐈‍⬛"
    text="GitHub"
    />

  </main>

  <StacksInfo :stacks="stacks" 
  />

</template>

<script setup>
const stacks = [
  { name: "AWS", logo: "/logos/icons8-aws-48.png" },
  { name: "Azure", logo: "/logos/icons8-azure-48.png" },
  { name: "GCP", logo: "/logos/icons8-google-cloud-48.png" },
  { name: "Docker", logo: "/logos/icons8-docker-48.png" },
  { name: "Kubernetes", logo: "/logos/icons8-kubernetes-48.png" },
  { name: "Apache Spark", logo: "/logos/icons8-apache-spark-48.png" },
  { name: "Apache kafka", logo: "/logos/icons8-apache-kafka-64.png" },
  { name: "Databricks", logo: "/logos/databricks.png" },
  { name: "Hadoop", logo: "/logos/icons8-sistema-de-arquivos-distribuídos-do-hadoop-48.png" },
  { name: "PostgreSQL", logo: "/logos/icons8-postgresql-48.png" },
  { name: "MySQL", logo: "/logos/icons8-mysql-48.png" },
  { name: "MongoDB", logo: "/logos/icons8-mongo-db-48.png" },
  { name: "Python", logo: "/logos/icons8-python-48.png" },
  { name: "Java", logo: "/logos/icons8-logo-java-coffee-cup-48.png" },
  { name: "C++", logo: "/logos/icons8-c-48.png" },
  { name: "", logo: "" },
];
</script>