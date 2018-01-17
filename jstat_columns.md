<table class="table table-hover table-mc-indigo">
	<thead>
		<tr>
			<td>Column</td>
			<td style="width:530px">Description</td>
			<td>Jstat Option</td>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>S0C</td>
			<td>Displays the current size of Survivor0 area in KB</td>
			<td>-gc<br>
			-gccapacity<br>
			-gcnew<br>
			-gcnewcapacity</td>
		</tr>
		<tr>
			<td>S1C</td>
			<td>Displays the current size of Survivor1 area in KB</td>
			<td>-gc<br>
			-gccapacity<br>
			-gcnew<br>
			-gcnewcapacity</td>
		</tr>
		<tr>
			<td>S0U</td>
			<td>Displays the current usage of Survivor0 area in KB</td>
			<td>-gc<br>
			-gcnew</td>
		</tr>
		<tr>
			<td>S1U</td>
			<td>Displays the current usage of Survivor1 area in KB</td>
			<td>-gc<br>
			-gcnew</td>
		</tr>
		<tr>
			<td>EC</td>
			<td>Displays the current size of Eden area in KB</td>
			<td>-gc<br>
			-gccapacity<br>
			-gcnew<br>
			-gcnewcapacity</td>
		</tr>
		<tr>
			<td>EU</td>
			<td>Displays the current usage of Eden area in KB</td>
			<td>-gc<br>
			-gcnew</td>
		</tr>
		<tr>
			<td>OC</td>
			<td>Displays the current size of old area in KB</td>
			<td>-gc<br>
			-gccapacity<br>
			-gcold<br>
			-gcoldcapacity</td>
		</tr>
		<tr>
			<td>OU</td>
			<td>Displays the current usage of old area in KB</td>
			<td>-gc<br>
			-gcold</td>
		</tr>
		<tr>
			<td>PC</td>
			<td>Displays the current size of permanent area in KB</td>
			<td>-gc<br>
			-gccapacity<br>
			-gcold<br>
			-gcoldcapacity<br>
			-gcpermcapacity</td>
		</tr>
		<tr>
			<td>PU</td>
			<td>Displays the current usage of permanent area in KB</td>
			<td>-gc<br>
			-gcold</td>
		</tr>
		<tr>
			<td>YGC</td>
			<td>The number of GC event occurred in young area</td>
			<td>-gc<br>
			-gccapacity<br>
			-gcnew<br>
			-gcnewcapacity<br>
			-gcold<br>
			-gcoldcapacity<br>
			-gcpermcapacity<br>
			-gcutil<br>
			-gccause</td>
		</tr>
		<tr>
			<td>YGCT</td>
			<td>The accumulated time for GC operations for Yong area <span></span></td>
			<td>-gc<br>
			-gcnew<br>
			-gcutil<br>
			-gccause</td>
		</tr>
		<tr>
			<td>FGC</td>
			<td>The number of full GC event occurred</td>
			<td>-gc<br>
			-gccapacity<br>
			-gcnew<br>
			-gcnewcapacity<br>
			-gcold<br>
			-gcoldcapacity<br>
			-gcpermcapacity<br>
			-gcutil<br>
			-gccause</td>
		</tr>
		<tr>
			<td>FGCT</td>
			<td>The accumulated time for full GC operations <span></span></td>
			<td>-gc<br>
			-gcold<br>
			-gcoldcapacity<br>
			-gcpermcapacity<br>
			-gcutil<br>
			-gccause</td>
		</tr>
		<tr>
			<td>GCT</td>
			<td>The total accumulated time for GC operations</td>
			<td>-gc<br>
			-gcold<br>
			-gcoldcapacity<br>
			-gcpermcapacity<br>
			-gcutil<br>
			-gccause</td>
		</tr>
		<tr>
			<td>NGCMN</td>
			<td>The minimum size of new area in KB</td>
			<td>-gccapacity<br>
			-gcnewcapacity</td>
		</tr>
		<tr>
			<td>NGCMX</td>
			<td>The maximum size of max area in KB <span> </span></td>
			<td>-gccapacity<br>
			-gcnewcapacity</td>
		</tr>
		<tr>
			<td>NGC</td>
			<td>The current size of new area in KB <span> </span></td>
			<td>-gccapacity<br>
			-gcnewcapacity</td>
		</tr>
		<tr>
			<td>OGCMN</td>
			<td>The minimum size of old area in KB</td>
			<td>-gccapacity<br>
			-gcoldcapacity</td>
		</tr>
		<tr>
			<td>OGCMX</td>
			<td>The maximum size of old area in KB</td>
			<td>-gccapacity<br>
			-gcoldcapacity</td>
		</tr>
		<tr>
			<td>OGC</td>
			<td>The current size of old area in KB <span> </span></td>
			<td>-gccapacity<br>
			-gcoldcapacity</td>
		</tr>
		<tr>
			<td>PGCMN</td>
			<td>The minimum size of permanent area in KB</td>
			<td>-gccapacity<br>
			-gcpermcapacity</td>
		</tr>
		<tr>
			<td>PGCMX</td>
			<td>The maximum size of permanent area in KB</td>
			<td>-gccapacity<br>
			-gcpermcapacity</td>
		</tr>
		<tr>
			<td>PGC</td>
			<td>The current size of permanent generation area in KB</td>
			<td>-gccapacity<br>
			-gcpermcapacity</td>
		</tr>
		<tr>
			<td>PC</td>
			<td>The current size of permanent area in KB</td>
			<td>-gccapacity<br>
			-gcpermcapacity</td>
		</tr>
		<tr>
			<td>PU</td>
			<td>The current usage of permanent area in KB <span></span></td>
			<td>-gc<br>
			-gcold</td>
		</tr>
		<tr>
			<td>LGCC</td>
			<td>The cause for the last GC occurrence <span></span></td>
			<td>-gccause</td>
		</tr>
		<tr>
			<td>GCC</td>
			<td>The cause for the current GC occurrence</td>
			<td>-gccause</td>
		</tr>
		<tr>
			<td>TT</td>
			<td>Tenuring threshold. If copied this amount of times in young area (S0 -&gt;S1, S1-&gt;S0), they are then moved to old area.</td>
			<td>-gcnew</td>
		</tr>
		<tr>
			<td>MTT</td>
			<td>Maximum Tenuring threshold. If copied this amount of times inside young arae, then they are moved to old area.</td>
			<td>-gcnew</td>
		</tr>
		<tr>
			<td>DSS</td>
			<td>Adequate size of survivor in KB<span>&nbsp; </span><span></span></td>
			<td>-gcnew</td>
		</tr>
	</tbody>
</table>
