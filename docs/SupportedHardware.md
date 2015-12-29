Hardware Support
================
Because of the HTML formatting, this page may be best viewed from
<http://opennetlinux.org/hcl>


Quanta
------
<table class="table table-striped table-hover">
<thead>
<tr class="info"> 
     <th> Device                  <th> Ports            <th> CPU                 <th> Forwarding             		<th> Support Status         <th> Forwarding Agents </tr>
</thead>
<tr> <td> QuantaMesh T1048-LB9    <td> 48x1G  + 4x10G   <td> FreeScale P2020       <td> Broadcom BCM56534 (Firebolt3)    	<td> Supported and Tested  <td> ORC </tr>
<tr> <td> QuantaMesh T1048-LB9A   <td> 48x1G  + 4x10G   <td> FreeScale P2020       <td> Broadcom BCM56534 (Firebolt3)    	<td> Supported, no ONIE, not regularly tested <td> ORC   </tr>
<tr> <td> QuantaMesh T3048-LY2    <td> 48x10G + 4x40G   <td> FreeScale P2020       <td> Broadcom BCM56846 (Trident+)     	<td> Supported and Tested  <td> ORC </tr>
<tr> <td> QuantaMesh T3048-LY8    <td> 48x10G + 6x40G   <td> Intel Rangely C2758 x86 <td> Broadcom BCM56854 (Trident2)            <td> Supported and run in the lab <td> NONE </tr>
<tr> <td> QuantaMesh T5032-LY6    <td> 32x40G  <td> Intel Rangely C2758 x86 <td> Broadcom BCM56850 (Trident2)            <td> Supported and run in the lab   <td> NONE </tr>
</table>


Accton/Edge-Core
------
<table class="table table-striped table-hover">
<thead>
<tr class="info">
     <th> Device                  <th> Ports            <th> CPU                 <th> Forwarding             		<th> Support Status        <th> Forwarding Agents </tr> 
</thead>
<tr> <td> Accton AS4600-54T       <td> 48x1G  + 4x10G   <td> FreeScale P2020       <td> Broadcom BCM56540 (Apollo2)       <td> Supported and Tested   <td> ORC </tr>
<tr> <td> Accton AS5600-52X       <td> 48x10G  + 4x40G   <td> FreeScale P2020       <td> Broadcom BCM56846 (Trident+)      <td> Supported and Tested  <td> ORC </tr>
<tr> <td> Accton AS5610-52X       <td> 48x10G  + 4x40G   <td> FreeScale P2020       <td> Broadcom BCM56846 (Trident+)      <td> Supported and Tested  <td> ORC </tr>
<tr> <td> Accton AS5710-54X       <td> 48x10G + 6x40G   <td> FreeScale P2041       <td> Broadcom BCM56854 (Trident2)      <td> Supported and Tested   <td> ORC </tr>
<tr> <td> Accton AS6700-32X       <td> 32x40G           <td> FreeScale P2041       <td> Broadcom BCM56850 (Trident2)      <td> Supported and Tested   <td> ORC </tr>
<tr> <td> Accton AS5712-54X       <td> 48x10G + 6x40G   <td> Intel Rangely C2538 x86 <td> Broadcom BCM56854 (Trident2)      <td> Supported and Tested <td> ORC </tr>
<tr> <td> Accton AS6712-32X       <td> 32x40G           <td> Intel Rangely C2538 x86 <td> Broadcom BCM56850 (Trident2)      <td> Supported and Tested <td> ORC </tr>
<tr> <td> Accton AS5812-54T       <td> 48x10G + 6x40G   <td> Intel Rangely C2538 x86 <td> Broadcom BCM56864 (Trident2+)      <td> Supported <td> NONE </tr>
<tr> <td> Accton AS5812-54X       <td> 48x10G + 6x40G   <td> Intel Rangely C2538 x86 <td> Broadcom BCM56864 (Trident2+)      <td> Supported <td> NONE </tr>
<tr> <td> Accton AS6812-32X       <td> 32x40G           <td> Intel Rangely C2538 x86 <td> Broadcom BCM56864 (Trident2+)      <td> Supported <td> NONE </tr>
</table>

DNI/Agema
---
<table class="table table-striped table-hover">
<thead>
<tr class="info">
     <th> Device                  <th> Ports            <th> CPU                 <th> Forwarding             <th> Support Status         </tr>
</thead>
<tr> <td> AG-7448CU               <td> 48x10G  + 4x40G  <td> FreeScale P2020       <td> Broadcom BCM56845 (Trident)     <td> Supported and Tested   </tr>
</table>

Dell
---
<table class="table table-striped table-hover">
<thead>
<tr class="info">
     <th> Device                  <th> Ports            <th> CPU                 <th> Forwarding             <th> Support Status         </tr>
</thead>
<tr> <td> S4810-ON            <td> 48x10G  + 4x40G  <td> FreeScale P2020        <td> Broadcom BCM56845 (Trident)     <td> Supported and Tested   </tr>
<tr> <td> S4048-ON            <td> 48x10G  + 6x40G  <td> Intel Atom C2338       <td> Broadcom BCM56854 (Trident2)     <td> Supported and Tested   </tr>
<tr> <td> S6000-ON            <td> 32x40G           <td> Intel Atom S1220       <td> Broadcom BCM56850 (Trident2)     <td> Supported and Tested   </tr>
</table>

Interface Masters Technologies, Inc.
---
<table class="table table-striped table-hover">
<thead>
<tr class="info">
     <th> Device          <th> Ports       <th> CPU        <th> Forwarding       <th> Modular I/O configurations       <th> Support Status     </tr>
</thead>
<tr> <td> Niagara 2948X12XLm   <td> 48x10G  + 12x40G  <td> Intel/AMD x86    <td> Broadcom BCM56850 (Trident2)   <td> Yes    <td> Supported and Tested by IMT   </tr>
<tr> <td> Niagara 2960X6XLm    <td> 60x10G  + 6x40G   <td> Intel/AMD x86    <td> Broadcom BCM56850 (Trident2)   <td> Yes    <td> Supported and Tested by IMT  </tr>
<tr> <td> Niagara 2972Xm       <td> 72x10G            <td> Intel/AMD x86    <td> Broadcom BCM56850 (Trident2)   <td> Yes    <td> Supported and Tested by IMT   </tr>
<tr> <td> Niagara 2932XL       <td> 32x40G            <td> Intel/AMD x86    <td> Broadcom BCM56850 (Trident2)   <td> No     <td> Supported and Tested by IMT   </tr>
<tr> <td> Niagara 2948X6XL     <td> 48x10G  + 6x40G   <td> Intel/AMD x86    <td> Broadcom BCM56850 (Trident2)   <td> No     <td> Supported and Tested by IMT   </tr>
</table>
