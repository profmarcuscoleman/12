<form action="https://www.paypal.com/cgi-bin/webscr" method="post">

<!-- Identify your business so that you can bill for payments. -->
<input type="hidden" name="business" value="your-secure-merchant-ID">

<!-- Specify an Installment Plan button. -->
<input type="hidden" name="cmd" value="_xclick-payment-plan">

<!-- Specify details about the installment plan. -->
<input type="hidden" name="currency_code" value="USD">
<input type="hidden" name="item_name" value="Electric Oven">
<input type="hidden" name="disp_tot" value="Y">

<!-- Make sure you get the buyer's address during checkout. -- >
<input type="hidden" name="no_shipping" value="2">

<!-- Set up 2 plan options for buyers to choose. -->
<input type="hidden" name="option_select0" value="option_0">
<input type="hidden" name="option_select0_name"
value="Pay In Full">
<input type="hidden" name="option_select0_type" value="F">
<input type="hidden" name="option_select0_a0" value="950.00">
<input type="hidden" name="option_select0_p0" value="1">
<input type="hidden" name="option_select0_t0" value="D">
<input type="hidden" name="option_select0_n0" value="1">
<input type="hidden" name="option_select1" value="option_1">
<input type="hidden" name="option_select1_name"
value="No Payment for 30 Days">
<input type="hidden" name="option_select1_type" value="E">
<input type="hidden" name="option_select1_a0" value="0.00">
<input type="hidden" name="option_select1_p0" value="1">
<input type="hidden" name="option_select1_t0" value="M">
<input type="hidden" name="option_select1_n0" value="1">
<input type="hidden" name="option_select1_a1" value="950.00">
<input type="hidden" name="option_select1_p1" value="1">
<input type="hidden" name="option_select1_t1" value="M">
<input type="hidden" name="option_select1_n1" value="1">
<input type="hidden" name="option_select1_a2" value="950.00">
<input type="hidden" name="option_select1_p2" value="1">
<input type="hidden" name="option_select1_t2" value="M">
<input type="hidden" name="option_select1_n2" value="3">
<input type="hidden" name="option_select2" value="option_2">
<input type="hidden" name="option_select2_name"
value="No Payment for 30 Days">
<input type="hidden" name="option_select2_type" value="E">
<input type="hidden" name="option_select2_a0" value="0.00">
<input type="hidden" name="option_select2_p0" value="1">
<input type="hidden" name="option_select2_t0" value="M">
<input type="hidden" name="option_select2_n0" value="1">
<input type="hidden" name="option_select2_a1" value="950.00">
<input type="hidden" name="option_select2_p1" value="1">
<input type="hidden" name="option_select2_t1" value="M">
<input type="hidden" name="option_select2_n1" value="1">
<input type="hidden" name="option_select2_a2" value="317.00">
<input type="hidden" name="option_select2_p2" value="1">
<input type="hidden" name="option_select2_t2" value="M">
<input type="hidden" name="option_select2_n2" value="3">

<input type="hidden" name="option_select3" value="option_3">
<input type="hidden" name="option_select3_name"
value="No Payment for 30 Days">
<input type="hidden" name="option_select3_type" value="E">
<input type="hidden" name="option_select3_a0" value="0.00">
<input type="hidden" name="option_select3_p0" value="1">
<input type="hidden" name="option_select3_t0" value="M">
<input type="hidden" name="option_select3_n0" value="1">
<input type="hidden" name="option_select3_a1" value="550.00">
<input type="hidden" name="option_select3_p1" value="1">
<input type="hidden" name="option_select3_t1" value="M">
<input type="hidden" name="option_select3_n1" value="1">
<input type="hidden" name="option_select3_a2" value="193.00">
<input type="hidden" name="option_select3_p2" value="1">
<input type="hidden" name="option_select3_t2" value="M">
<input type="hidden" name="option_select3_n2" value="3">



<input type="hidden" name="option_index" value="0">

<td><strong>ICPA: INSPIRE Academic Program with In-Classroom Teacher Support</strong></td>

<!-- Display 3 plan options for buyers to choose. -->
<table>
<tr>
<td colspan="3"><input type="hidden" name="on0" value="plans"></td></tr>

<!-- Pay in Full plan option -->
<tr>
<td><input type="radio" name="os0" value ="option_0"
checked="checked"></td>
<td><strong>Pay In Full </strong></td>
</tr>
<tr>
<td></td>
<td>Amount at checkout $1900.00 USD</td>
</tr>

<!-- Option 2 - 3 month Plan -->
<tr>
<td><input type="radio" name="os0" value ="option_
1"></td>
<td><strong>Option 2 -  2 Month Plan</strong></td>
</tr>
<tr>
<td></td>
<td>Number of payments: 2</td>
</tr>
<tr>
<td></td>
<td>Start payments after 1 month</td></tr>
<tr>
<td></td>
<td>
<table>
<tr>
<th>Due*</th>
<th>Amount</th>
</tr>
<tr>
<td colspan="2"><hr /></td></tr>
<tr>
<td>First Payment</td>
<td>$950.00 USD</td>
</tr>
<tr>
<td>Second Payment (x 2)</td>
<td>$950.00 USD</td>
</tr>
<tr>
<td colspan="2"><hr /></td>
</tr>
<tr>
<td colspan="2"><b>
Total&nbsp;&nbsp;&nbsp;
$950.00 USD</b></td>
</tr>
</table></td></tr>
<tr>
<td colspan="3"><i>* We calculate payments from the
date of checkout.</i></td>
</tr>
</table>



<!-- Option 2 - 3 month Plan -->
<tr>
<td><input type="radio" name="os0" value ="option_
2"></td>
<td><strong>Option 3 – 3 Month Plan</strong></td>
</tr>
<tr>
<td></td>
<td>Number of payments: 4</td>
</tr>
<tr>
<td></td>
<td>Start payments after 1 month</td></tr>
<tr>
<td></td>
<td>
<table>
<tr>
<th>Due*</th>
<th>Amount</th>
</tr>
<tr>
<td colspan="2"><hr /></td></tr>
<tr>
<td>First Payment</td>
<td>$950.00 USD</td>
</tr>
<tr>
<td>Every 1 month (x 3)</td>
<td>$317.00 USD</td>
</tr>
<tr>
<td colspan="2"><hr /></td>
</tr>
<tr>
<td colspan="2"><b>
Total&nbsp;&nbsp;&nbsp;
$950.00 USD</b></td>
</tr>
</table></td></tr>
<tr>
<td colspan="3"><i>* We calculate payments from the
date of checkout.</i></td>
<br>
</tr>
</table>



<!-- Option 3 - 6 month Plan -->
<tr>
<td><input type="radio" name="os0" value ="option_
3"></td>
<td><strong>Option 4 - 7 month Plan</strong></td>
</tr>
<tr>
<td></td>
<td>Number of payments: 7</td>
</tr>
<tr>
<td></td>
<td>Start payments after 1 month</td></tr>
<tr>
<td></td>
<td>
<table>
<tr>
<th>Due*</th>
<th>Amount</th>
</tr>
<tr>
<td colspan="2"><hr /></td></tr>
<tr>
<td>First Payment</td>
<td>$550.00 USD</td>
</tr>
<tr>
<td>Every 1 month (x 3)</td>
<td>$193.00 USD</td>
</tr>
<tr>
<td colspan="2"><hr /></td>
</tr>
<tr>
<td colspan="2"><b>
Total&nbsp;&nbsp;&nbsp;
$550.00 USD</b></td>
</tr>
</table></td></tr>
<tr>
<td colspan="3"><i>* We calculate payments from the
date of checkout.</i></td>
</tr>
</table>


<!-- Display the Installment Plan button -->
<table>
<tr><td><i>Sign up for</i></td></tr>
<tr><td><input type="image" name="submit"
src="https://www.paypalobjects.com/en_US/i/btn/btn_installment_plan_LG.gif"
alt="PayPal - The safer, easier way to pay online!"></td></tr>
</table>

<img alt="" width="1" height="1"
src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif"
</form>
