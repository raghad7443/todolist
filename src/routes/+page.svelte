<script lang="ts">
import dayjs from 'dayjs';
 import 'dayjs/locale/ar';
 dayjs.locale('ar');
</script>


<div class="p-16">

	<header class=" flex justify-between">
		<div>
			<h1 class=" text-4xl mb-3"> <!-- put the day and the greeting messge in the same div-->
				صباح الخير👋
			   </h1>
			   <h2 class=" text-2xl text-surface-800/70">
				{dayjs().format('اليوم ,dddd D MMM YYYY')}
			   </h2>
		</div>
		<div class="bg-slate-500 h-14 w-32 ">

		</div>
		</header>

</div>