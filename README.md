nyroModal-bootstrap jQuery Plugin
=======================
Fork of [nyroModal](https://github.com/nyroDev/nyroModal), that uses twitter bootstrap for markup.

###Usage

nyroModal-bootstrap doesn't provide contents of modal form, only wrapper with class "modal". Example of form inside:
<pre>
	<div class="modal-header">
		<a href="#" class="nyroModalClose close">&times;</a>
		<h3>Form example</h3>
	</div>
	<form method="post" action="" class="nyroModal">
		<fieldset class="modal-body">
			<div class="clearfix">
				<label for="example">Form example</label>
				<div class="input">
					<input class="" name="example" value="" id="example" />
				</div>
			</div>
		</fieldset>
		<div class="modal-footer">
			<input class="btn primary" type="submit" value="Submit" />
			<a href="#" class="btn nyroModalClose">Cancel</a>
		</div>
	</form>
</pre>

###Credits

All credits goes to [nyroDev](https://github.com/nyroDev)