<div class="fixed-bottom payment-borrad shadow bg-white m-3 rounded-1 p-3">
<div class="d-flex small">
<p>Total Payable USD</p>
<p class="ml-auto font-weight-bold text-danger">$53</p>
</div>
<div class="d-flex small">
<form class="w-100" action="javascript:;">
<div class="form-group mb-2">
<div class="d-flex align-items-start">
<label for="exampleInputEmail1" class="mb-1 small text-muted">Card Number</label>
<img src="img/master-card.png" class="img-fluid ml-auto rounded">
</div>
<input type="number" class="form-control form-control-sm" placeholder="1234 5678 9145 4589" id="exampleInputEmail1" aria-describedby="emailHelp">
</div>
<div class="form-group row mb-3">
<div class="col-8">
<label for="exampleInputmondate1" class="mb-1 small text-muted">Month / Date</label>
<div class="d-flex border rounded">
<input type="number" class="form-control text-center form-control-sm border-0 px-1" placeholder="DD" id="exampleInputmondate1" aria-describedby="mondateHelp">
<span class="pt-2">/</span>
<input type="number" class="form-control text-center form-control-sm border-0 px-1" placeholder="MM" id="exampleInputmondate1" aria-describedby="mondateHelp">
</div>
</div>
<div class="col-4">
<label for="exampleInputcvv1" class="mb-1 small text-muted">CVV</label>
<input type="number" class="form-control text-center form-control-sm" placeholder="000" id="exampleInputcvv1" aria-describedby="cvvHelp">
</div>
</div>
<button type="submit" class="btn btn-danger btn-block" data-toggle="modal" data-target="#paymentModal">Pay</button>
</form>
</div>
</div>