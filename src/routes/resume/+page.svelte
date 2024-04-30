<script>
	import { writable } from 'svelte/store';

	let showModal = writable(false);

	function toggleModal() {
		showModal.update((n) => !n);
	}
</script>

<div class="relative ml-16 max-w-lg">
	<!-- Download and social links -->
	<div class="absolute right-0 top-0 flex gap-2 p-4">
		<a
			href="/path/to/file.pdf"
			download="filename.pdf"
			class="rounded-lg border border-gray-200 bg-white px-2 py-1 text-sm text-gray-900 hover:bg-gray-100"
			>PDF</a
		>
		<a
			href="/path/to/file.doc"
			download="filename.doc"
			class="rounded-lg border border-gray-200 bg-white px-2 py-1 text-sm text-gray-900 hover:bg-gray-100"
			>DOC</a
		>
		<a
			href="/path/to/file.txt"
			download="filename.txt"
			class="rounded-lg border border-gray-200 bg-white px-2 py-1 text-sm text-gray-900 hover:bg-gray-100"
			>TXT</a
		>
	</div>
</div>

Daniel Luedke

<div class="ml-6 max-w-lg">
	<ol class="relative border-s border-gray-200 dark:border-gray-700">
		<li class="mb-10 ms-4">
			<div
				class="absolute -start-1.5 mt-1.5 h-3 w-3 rounded-full border border-white bg-gray-200 dark:border-gray-900 dark:bg-gray-700"
			></div>
			<time class="mb-1 text-sm font-normal leading-none text-gray-400 dark:text-gray-500"
				>Aug 2022 - Nov 2023</time
			>
			<h3 class="text-lg font-semibold text-gray-900 dark:text-gray-800">
				<a href="https://synopsys.com">Synopsys</a>
			</h3>
			<h4 class="text-sm font-semibold text-gray-500 dark:text-gray-800">Staff Sales Engineer</h4>
			<p class="mb-4 text-base font-normal text-gray-500 dark:text-gray-400">
				Enterprise sales engineering for comprehensive security testing tools within the CI pipeline
				to enhance software security and compliance.
			</p>
			<a
				href="/resume/synopsys"
				class="inline-flex items-center rounded-lg border border-gray-200 bg-white px-4 py-2 text-sm font-medium text-gray-900 hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:text-blue-700 focus:outline-none focus:ring-4 focus:ring-gray-100 dark:border-gray-600 dark:bg-gray-800 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white dark:focus:ring-gray-700"
				>Learn more <svg
					class="ms-2 h-3 w-3 rtl:rotate-180"
					aria-hidden="true"
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 14 10"
				>
					<path
						stroke="currentColor"
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M1 5h12m0 0L9 1m4 4L9 9"
					/>
				</svg></a
			>
		</li>
		<li class="mb-10 ms-4">
			<div
				class="absolute -start-1.5 mt-1.5 h-3 w-3 rounded-full border border-white bg-gray-200 dark:border-gray-900 dark:bg-gray-700"
			></div>
			<time class="mb-1 text-sm font-normal leading-none text-gray-400 dark:text-gray-500"
				>Mar 2021 - Jan 2022 </time
			>
			<h3 class="text-lg font-semibold text-gray-900 dark:text-gray-800">
				<a href="https://nobl9.com">Nobl9</a>
			</h3>
			<h4 class="text-sm font-semibold text-gray-500 dark:text-gray-800">
				Product Marketing Manager
			</h4>
			<p class="mb-4 text-base font-normal text-gray-500 dark:text-gray-400">
				Helping SRE teams deploy Service Level Objectives (SLOs) with error-budgets.
			</p>
			<a
				href="/resume/nobl9"
				class="inline-flex items-center rounded-lg border border-gray-200 bg-white px-4 py-2 text-sm font-medium text-gray-900 hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:text-blue-700 focus:outline-none focus:ring-4 focus:ring-gray-100 dark:border-gray-600 dark:bg-gray-800 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white dark:focus:ring-gray-700"
				>Learn more <svg
					class="ms-2 h-3 w-3 rtl:rotate-180"
					aria-hidden="true"
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 14 10"
				>
					<path
						stroke="currentColor"
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M1 5h12m0 0L9 1m4 4L9 9"
					/>
				</svg></a
			>
		</li>
		<li class="mb-10 ms-4">
			<div
				class="absolute -start-1.5 mt-1.5 h-3 w-3 rounded-full border border-white bg-gray-200 dark:border-gray-900 dark:bg-gray-700"
			></div>
			<time class="mb-1 text-sm font-normal leading-none text-gray-400 dark:text-gray-500"
				>Jun 2018 - Jan 2020</time
			>
			<h3 class="text-lg font-semibold text-gray-900 dark:text-gray-800">Dragonchain</h3>
			<h4 class="text-sm font-semibold text-gray-500 dark:text-gray-800">
				Director of Product Marketing
			</h4>
			<p class="mb-4 text-base font-normal text-gray-500 dark:text-gray-400">
				Go to market plan for early stage startup. Disney's largest open source project.
			</p>
			<a
				href="/resume/dragonchain"
				class="inline-flex items-center rounded-lg border border-gray-200 bg-white px-4 py-2 text-sm font-medium text-gray-900 hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:text-blue-700 focus:outline-none focus:ring-4 focus:ring-gray-100 dark:border-gray-600 dark:bg-gray-800 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white dark:focus:ring-gray-700"
				>Learn more <svg
					class="ms-2 h-3 w-3 rtl:rotate-180"
					aria-hidden="true"
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 14 10"
				>
					<path
						stroke="currentColor"
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M1 5h12m0 0L9 1m4 4L9 9"
					/>
				</svg></a
			>
		</li>
		<li class="mb-10 ms-4">
			<div
				class="absolute -start-1.5 mt-1.5 h-3 w-3 rounded-full border border-white bg-gray-200 dark:border-gray-900 dark:bg-gray-700"
			></div>
			<time class="mb-1 text-sm font-normal leading-none text-gray-400 dark:text-gray-500"
				>Sep 2011 - Jun 2018</time
			>
			<h3 class="text-lg font-semibold text-gray-900 dark:text-gray-800">F5</h3>
			<h4 class="text-sm font-semibold text-gray-500 dark:text-gray-800">
				Product Marketing Manager
			</h4>
			<p class="mb-4 text-base font-normal text-gray-500 dark:text-gray-400">
				Managed the go to market for the core BIG-IP load balancer and security products.
			</p>
			<a
				href="/resume/f5"
				class="inline-flex items-center rounded-lg border border-gray-200 bg-white px-4 py-2 text-sm font-medium text-gray-900 hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:text-blue-700 focus:outline-none focus:ring-4 focus:ring-gray-100 dark:border-gray-600 dark:bg-gray-800 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white dark:focus:ring-gray-700"
				>Learn more <svg
					class="ms-2 h-3 w-3 rtl:rotate-180"
					aria-hidden="true"
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 14 10"
				>
					<path
						stroke="currentColor"
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M1 5h12m0 0L9 1m4 4L9 9"
					/>
				</svg></a
			>
		</li>
		<li class="mb-10 ms-4">
			<div
				class="absolute -start-1.5 mt-1.5 h-3 w-3 rounded-full border border-white bg-gray-200 dark:border-gray-900 dark:bg-gray-700"
			></div>
			<time class="mb-1 text-sm font-normal leading-none text-gray-400 dark:text-gray-500"
				>May 2004 - Sep 2011</time
			>
			<h3 class="text-lg font-semibold text-gray-900 dark:text-gray-800">
				Network Computing Architects
			</h3>
			<h4 class="text-sm font-semibold text-gray-500 dark:text-gray-800">
				Sr. Sales Engineer / Security Analysis Practice Manager
			</h4>
			<p class="mb-4 text-base font-normal text-gray-500 dark:text-gray-400">
				Managed the go to market for the core BIG-IP load balancer and security products.
			</p>
			<a
				href="/resume/nca"
				class="inline-flex items-center rounded-lg border border-gray-200 bg-white px-4 py-2 text-sm font-medium text-gray-900 hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:text-blue-700 focus:outline-none focus:ring-4 focus:ring-gray-100 dark:border-gray-600 dark:bg-gray-800 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white dark:focus:ring-gray-700"
				>Learn more <svg
					class="ms-2 h-3 w-3 rtl:rotate-180"
					aria-hidden="true"
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 14 10"
				>
					<path
						stroke="currentColor"
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M1 5h12m0 0L9 1m4 4L9 9"
					/>
				</svg></a
			>
		</li>

	

</div>
<div class="relative mx-4 max-w-lg">
	<!-- Download and social links -->
	<div class="absolute right-0 top-0 flex gap-2 p-4">
		<!-- Social links -->
		<a
			href="https://github.com/break-the-build"
			target="_blank"
			class="rounded-lg border border-gray-200 bg-white px-2 py-1 text-sm text-gray-900 hover:bg-gray-100"
			>GitHub</a
		>
		<a
			href="https://www.linkedin.com/in/daniel-louis-luedke/"
			target="_blank"
			class="rounded-lg border border-gray-200 bg-white px-2 py-1 text-sm text-gray-900 hover:bg-gray-100"
			>LinkedIn</a
		>
	</div>
</div>
