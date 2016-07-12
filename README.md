# Flexbox grid
Lightweight grid system based on flexbox

Define your settings in grid.css:
	:root {
		--max-width: 1600px;
		--gutter-width: 1rem;
		--outer-margin: 1rem;
	}

To use a max-width, add .container-fixed to your wrapper:
	<div class="container container-fixed">
		<div class="row">
		    <div class="col is-12">12 columns</div>
		</div>
	</div>

Adding columns is easy:
	<div class="row">
        <div class="col is-10">10 columns</div>
        <div class="col is-2">2 columns</div>
    </div>

Columns with offset:
	<div class="row">
	    <div class="col is-3 is-pushed-2">3 columns (2 column offset)</div></div>
	    <div class="col is-4 is-pushed-3">4 columns (3 column offset)</div></div>
	</div>