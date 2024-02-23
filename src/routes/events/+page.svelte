<script>
// @ts-nocheck

	// get data returned during page load
	export let data;

	// get data
	let computers = data.computers;
	let events = data.events;
	
</script>

<!-- The HTML content of the page-->

<div class="container">
	<div class="row">
		<!-- Page Header -->
		<h2 class="mt-5">Events Log from Supabase</h2>
	</div>
	<div class="row">
		<div class="col-sm-2">
			<!-- Page Body Left Column (menu) -->
			<div id="computers" class="list-group">
				<!-- computer links -->
				<button class="list-group-item list-group-item-action"> All Computers </button>
				<button class="list-group-item list-group-item-action"> Computer 1 </button>
				<button class="list-group-item list-group-item-action"> Computer 2 </button>
				<button class="list-group-item list-group-item-action"> Computer 3 </button>
			</div>
		</div>
		<!-- End computer col -->
		<div class="col-sm-10">
			<!-- Page Body Right Side (Content goes here) -->
			<div id="events">
				<table class="table table-striped table-bordered table-hover">
					<thead>
						<tr>
							<th>id</th>
							<th>Computer</th>
							<th>Description</th>
							<th>Level</th>
							<th>Service</th>
							<th>Type</th>
							<th>User</th>
						</tr>
					</thead>
					<tbody
						><tr>
							<td>event id</td>
							<td>event computer</td>
							<td>event description</td>
							<td>event level </td>
							<td>event service</td>
							<td>event type</td>
							<td>event user</td>
						</tr>
					</tbody>
				</table>
			</div>
		</div>
		<!-- End events col -->
	</div>
	<!-- End Row -->
</div>
<!-- End Main Content-->
