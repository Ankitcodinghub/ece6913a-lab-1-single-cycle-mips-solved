# ece6913a-lab-1-single-cycle-mips-solved
**TO GET THIS SOLUTION VISIT:** [ECE6913A Lab 1-Single Cycle MIPS Solved](https://www.ankitcodinghub.com/product/ece6913a-lab-1-single-cycle-mips-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93702&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE6913A Lab 1-Single Cycle MIPS Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<strong>&nbsp;&nbsp;Lab 1: Single Cycle MIPS</strong>

In this Lab assignment you will implement an instruction-level simulator for a single cycle MIPS processor in C++. The simulator supports a subset of the MIPS instruction set and can model the execution of each instruction.

An example MIPS program is provided for the simulator as a text file “imem.txt” file, which is used to initialize the Instruction Memory. Each line of the file corresponds to a Byte stored in the Instruction Memory in binary format, with the first line at address 0, the next line at address 1 and so on. Four contiguous lines correspond to one whole instruction. Note that the words stored in memory are in “Big-Endian” format, meaning that the most significant byte is stored first.

&nbsp;

We have also defined a “halt” instruction as 32’b1 (0xFFFFFFFF), which is the last instruction in every “imem.txt” file. As the name suggests, when this instruction is fetched, the simulation is terminated. We will provide a sample “imem.txt” file containing a MIPS program. You are strongly encouraged to generate other “imem.txt” files to test your simulator.

&nbsp;

The Data Memory is initialized using the “dmem.txt” file. The format of the stored words is the same as the Instruction Memory. As with the instruction memory, the data memory addresses also begin at 0 and increment by one in each line.

&nbsp;

The instructions that the simulator supports and their encodings are shown in Table 1. Note that all instructions, except for “halt”, exist in the MIPS ISA. The <em>MIPS Green Sheet</em> from HW1 defines the semantics of each instruction.

&nbsp;

&nbsp;

&nbsp;

<table width="474">
<tbody>
<tr>
<td width="144"><strong>Name</strong></td>
<td width="144"><strong>Format Type</strong></td>
<td width="102"><strong>Opcode</strong> <strong>(Hex)</strong></td>
<td width="84"><strong>Func</strong> <strong>(Hex)</strong></td>
</tr>
<tr>
<td width="144"><strong>addu</strong></td>
<td width="144">R-Type</td>
<td width="102">00</td>
<td width="84">21</td>
</tr>
<tr>
<td width="144"><strong>subu</strong></td>
<td width="144">R-Type</td>
<td width="102">00</td>
<td width="84">23</td>
</tr>
<tr>
<td width="144"><strong>addiu</strong></td>
<td width="144">I-Type</td>
<td width="102">09</td>
<td width="84"></td>
</tr>
<tr>
<td width="144"><strong>and</strong></td>
<td width="144">R-Type</td>
<td width="102">00</td>
<td width="84">24</td>
</tr>
<tr>
<td width="144"><strong>or</strong></td>
<td width="144">R-Type</td>
<td width="102">00</td>
<td width="84">25</td>
</tr>
<tr>
<td width="144"><strong>nor</strong></td>
<td width="144">R-Type</td>
<td width="102">00</td>
<td width="84">27</td>
</tr>
<tr>
<td width="144"><strong>beq</strong></td>
<td width="144">I-Type</td>
<td width="102">04</td>
<td width="84"></td>
</tr>
<tr>
<td width="144"><strong>j</strong></td>
<td width="144">J-Type</td>
<td width="102">02</td>
<td width="84"></td>
</tr>
<tr>
<td width="144"><strong>lw</strong></td>
<td width="144">I-Type</td>
<td width="102">23</td>
<td width="84"></td>
</tr>
<tr>
<td width="144"><strong>sw</strong></td>
<td width="144">I-Type</td>
<td width="102">2B</td>
<td width="84"></td>
</tr>
<tr>
<td width="144"><strong>halt</strong></td>
<td width="144">J-Type</td>
<td width="102">3F</td>
<td width="84"></td>
</tr>
</tbody>
</table>
Table 1. Instruction encodings for a reduced MIPS ISA

<strong><u>Skeleton Code</u></strong>

The file “MIPS.cpp” contains a skeleton code for the assignment. You need to fill in the missing code. In this section, we provide descriptions for each of the components in the skeleton code.

<strong>Classes</strong>

We have defined four C++ classes that each implement one of the four major blocks in a single cycle MIPS machine, namely RF (to implement the register file), ALU (to implement the ALU), INSMem (to implement instruction memory), and DataMem (to implement data memory).

&nbsp;

<ol>
<li><strong>RF class:</strong> contains 32 32-bit registers defined as a private member. Remember that register $0 is always 0. Your job is to implement the implement the <em>ReadWrite()</em> member function that provides read and write access to the register file.</li>
<li><strong>ALU class:</strong> implements the ALU. Your job is to implement <em>ALUOperation() </em>member function that performs the appropriate operation on two 32 bit operands based on ALUOP. See Table 1 for more details.</li>
<li><strong>INSMem class:</strong> a Byte addressable memory that contains instructions. The constructor <em>InsMem()</em> initializes the contents of instruction memory from the file imem.txt (this has been done for you). Your job is to implement the member function <em>ReadMemory()</em> that provides read access to instruction memory. An access to the instruction memory class returns 4 bytes of data; i.e., the byte pointed to by the address and the three subsequent bytes.</li>
<li><strong>DataMem class:</strong> is similar to the instruction memory, except that it provides both read and write access.</li>
</ol>
&nbsp;

<strong>Main Function</strong>

&nbsp;

The main function defines a 32 bit program counter (PC) that is initialized to zero. The MIPS simulation routine is carried out within a while loop. In each iteration of the while loop, you will fetch one instruction from the instruction memory, and based on the instruction, make calls to the register file, ALU and data memory classes (in fact, you might need to make two calls to the register file class, once to read and a second time to write back). Finally you will update the PC so as to fetch the next instruction. When the halt instruction is fetched, you are to break out of the while loop and terminate the simulation.

&nbsp;

Make sure that the architectural state is updated correctly after execution of <strong>each</strong> instruction. The architectural state consists of the Program Counter (PC), the Register File (RF) and the Data Memory (DataMem). We will check the correctness of the architectural state after <em>each</em> instruction.

&nbsp;

Specifically, the OutputRF() function is called at the end of each iteration of the while loop, and will add the new state of the Register File to “RFresult.txt”. Therefore, at the end of the program execution “RFresult.txt” contains all the intermediate states of the Register File. Once the program terminates, the OutputDataMem() function will write the final state of the Data Memory to “dmem.txt”. These functions have been implemented for you. Do not modify them.

(Note: <strong>You should delete the “RFresult.txt” file before re-executing your program</strong>, otherwise the new results will append to the previous results.)

<ol>
<li>A brief introduction to C++ (<a href="https://web.eecs.umich.edu/~sugih/pointers/c++.pdf">https://web.eecs.umich.edu/~sugih/pointers/c++.pdf</a>)</li>
<li>A reference for the C++ bitset class (<a href="http://www.cplusplus.com/reference/bitset/bitset/">http://www.cplusplus.com/reference/bitset/bitset/</a>)</li>
<li>A reference to the C++ string class (<a href="http://www.cplusplus.com/reference/string/string/">http://www.cplusplus.com/reference/string/string/</a>)</li>
</ol>
1
