<h3 align="center">Computer Organization and<br> Operating System Assignment</h3>
<p align="center">รายงานฉบับนี้เป็นส่วนหนึ่งของวิชา 06016412 COMPUTER ORGANIZATION AND OPERATING SYSTEM ชั้นปีที่ 2 (2/2023) โดยมีจุดประสงค์เพื่อศึกษาความรู้ที่ได้จากเรื่อง Process ของ Linux ซึ่งรายงานนี้นำเสนอความรู้พื้นฐานเกี่ยวกับProcess ใน Linux โดยอธิบายองค์ประกอบสำคัญของโพรเซส เช่น สถานะprocess การจัดการหน่วยความจำ และการจัดตารางเวลา รวมถึงการทำงานของprocessใน Linux เป้าหมายของรายงานนี้ คือ เพื่อช่วยให้ผู้อ่านเข้าใจระบบprocess ใน Linux และสามารถจัดการprocessต่างๆ บนคอมพิวเตอร์ได้อย่างมีประสิทธิภาพ</p>

<h3 align="center">Overview</h3>
<p align="center">ในระบบปฏิบัติการ Linux,  Process ใน Linux คือ เปรียบเสมือนโปรแกรมที่กำลังทำงานอยู่ เป็นหน่วยพื้นฐานของการประมวลผลในระบบ Linux แต่ละ process จะมีหน่วยความจำ พื้นที่ว่างบนดิสก์ และทรัพยากรระบบอื่นๆ ของตัวเอง ช่วยให้ผู้ใช้สามารถทำงานหลายอย่างพร้อมกัน ใช้ทรัพยากรอย่างมีประสิทธิภาพ และปรับแต่งระบบ Linux ให้ทำงานตามต้องการ</p>

<details>
  <summary style="font-size: 20px; font-weight: bold">Table of Contents</summary>
  <ol>
    <li>
      <a href="#introduction">Introduction</a>
      <ul>
        <li><a href="#process-components">Process components</a></li>
      </ul>
    </li>
    <li>
        <a href="#Heading">Heading</a>
        <ul><li><a href="#process-components">SubHeading</a></li></ul>
        <ul><li><a href="#process-components">SubHeading</a></li></ul>
        <ul><li><a href="#process-components">SubHeading</a></li></ul>
    </li>
    <li><a href="#Heading">Heading</a></li>
    <li><a href="#Heading">Heading</a></li>
    <li><a href="#Heading">Heading</a></li>
    <li><a href="#Heading">Heading</a></li>
    <li><a href="#Heading">Heading</a></li>
    <li><a href="#Heading">Heading</a></li>
  </ol>
</details>

# Introduction: Process
&emsp;&emsp;Process Components ใน Linux
คือส่วนหนึ่งของระบบปฏิบัติการที่จัดการกับการทำงานของกระบวนการ (Processes) ในระบบ ซึ่งรวมถึงการจัดการกระบวนการเริ่มต้น (Boot Process), การจัดการกระบวนการทั่วไป (Process Management), การจัดการบริการ (Service Management), และตัวตั้งเวลางาน (Task Scheduler) ที่มีบทบาทสำคัญในการทำงานของระบบปฏิบัติการ Linux.

# Process Componentss
ส่วนประกอบหลักของกระบวนการ:
1. Program: คือโค้ดของโปรแกรมที่ถูกโหลดไว้ในหน่วยความจำ.
2. Process State: ระบบติดตามสถานะของกระบวนการ, ได้แก่ กระบวนการที่กำลังทำงาน, กระบวนการที่รอ, และกระบวนการที่ถูกหยุด.
3. Process Status:
รวมถึงข้อมูลเกี่ยวกับการทำงานปัจจุบันของกระบวนการ เช่น ID ของกระบวนการ (PID), หมายเลขห้องประชุม (TTY), และเวลาที่ใช้ในการทำงาน.
4. Process Relationship: ระบบต้องการทราบว่ากระบวนการไหนเป็นโมเดลของกระบวนการไหน.

5. Stack Status: ข้อมูลที่ใช้ในการจัดการหน่วยความจำสำหรับการเรียกฟังก์ชัน.




> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.