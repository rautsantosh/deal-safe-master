<script>
  // core components
  import CardStats from "components/Cards/CardStats.svelte";
</script>

<!-- Header -->
<div class="relative bg-red-500 md:pt-32 pb-32 pt-12">
  <div class="px-4 md:px-10 mx-auto w-full">
    <div>
      <!-- Card stats -->
      <div class="flex flex-wrap">
        <div class="w-full lg:w-6/12 xl:w-3/12 px-4">
          <CardStats
            statSubtitle="My Contracts"
            statTitle="400"
            statArrow=""
            statPercent=""
            statPercentColor="text-red-500"
            statDescripiron=""
            statIconName="fas fa-chart-pie"
            statIconColor="bg-orange-500"
          />
        </div>
        <div class="w-full lg:w-6/12 xl:w-3/12 px-5">
          <CardStats
            statSubtitle="Pending Contracts"
            statTitle="90"
            statArrow=""
            statPercent=""
            statPercentColor="text-red-500"
            statDescripiron=""
            statIconName="fas fa-chart-pie"
            statIconColor="bg-orange-500"
          />
        </div>
        <div class="w-full lg:w-6/12 xl:w-3/12 px-4">
          <CardStats
            statSubtitle="In Progress"
            statTitle="50"
            statArrow=""
            statPercent=""
            statPercentColor="text-orange-500"
            statDescripiron=""
            statIconName="fas fa-users"
            statIconColor="bg-pink-500"
          />
        </div>
        <div class="w-full lg:w-6/12 xl:w-3/12 px-4">
          <CardStats
            statSubtitle="Closed"
            statTitle="260"
            statArrow=""
            statPercent=""
            statPercentColor="text-green-500"
            statDescripiron=""
            statIconName="fas fa-percent"
            statIconColor="bg-green-500"
          />
        </div>
      </div>
    </div>
  </div>
</div>
