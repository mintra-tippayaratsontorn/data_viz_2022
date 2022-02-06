# data_viz_2022
Introduction to Basic Programming for Data Science and Data Visualization : มินตรา ทิพยรัตน์สุนทร ID 623020041-2

# สารบัญเนื้อหา
* [introduction](https://github.com/mintra-tippayaratsontorn/data_viz_2022/blob/main/Intro0.ipynb)
* [Python101](https://github.com/mintra-tippayaratsontorn/data_viz_2022/blob/main/Python101.ipynb)
  * การจัดการข้อความในการแสดงผล (Print)
    * ข้อความ (string)
    * Print(ข้อความ)
  * ตัวแปร (Variables)
    * ข้อกำหนดในการตั้งชื่อตัวแปร
    * Advanced Printing
    * ชนิดของตัวแปร
      * char(acter)(ตัวอักษร)
      * int(eger)(จำนวนเต็ม)
      * float(จำนวนจริง ทศนิยม)
      * boolean (ตัวแปรที่มีค่า True หรือ False) ตรรกศาสตร์
      * complex (จำนวนเชิงซ้อน)
    * การแปลงชนิดของตัวแปร(Variable Casting)
    * Operation เอาตัวแปรสองตัวมาทำอะไรกัน
      * Operators (บวก (+) , ลบ (-) , คูณ (*) , หาร (/) , modulo (%) , and (&) , or (|)
    * (+) : concat (เอามาต่อกัน) , (*) : repeat (ซ้ำ)
    * replace() แทนที่ string
    * split() แยก string


* [Data Structure](https://github.com/mintra-tippayaratsontorn/data_viz_2022/blob/main/Data_Structure.ipynb)
  * list()
    * indexing การชี้สมาชิกใน list ด้วย เลขลำดับของ list
    * การสร้าง list()
    * เพิ่มสมาชิกเข้าไปใน list ด้วย append()
    * ลบสมาชิกจาก list
    * len() ตรวจสอบจำนวนสมาชิกของ list
    * String is a list of characters
    * List Slicing :
    * range()
  * Dictionary
    * สร้าง Dictionary
    * การชี้สมาชิกใน Dictionary
    * การเพิ่มสมาชิกเข้าไปใน Dictionary
  * Numpy Array
    * 1D array
    * 2D array
    * np.zero()
    * np.ones()
    * Matrix operation
      * การบวก ลบ matrix
      * การคูณ matrix
    * Matrix Slicing


* [Basic Programming Concepts](https://github.com/mintra-tippayaratsontorn/data_viz_2022/blob/main/Basic_Programming_Concepts.ipynb)
  * Functions ( f(x)=y )
    * function ที่มีส่วนประกอบครบ
    * function ที่ไม่มี input
    * function ไม่มี process ไม่ได้
    * function ที่ไม่มี output
    * function print
    * input ของ function แบ่งเป็น 2 ชนิด (จำเป็นต้องใส่ กับ ไม่จำเป็นต้องใส่)
  * Looping (for)
    * ใช้ for loop เพิ่มสมาชิกใน list
    * การวนลูปด้วย range()
    * Loop ซ้อน Loop
    * Loop in Function
  * Conditional Statement (if)
    * operation ที่ใช้ตรวจสอบ condition


* [Pandas101](https://github.com/mintra-tippayaratsontorn/data_viz_2022/blob/main/Pandas101.ipynb)
  * load data to memory
  * ชี้ค่าในตาราง
    * basic
    * .iloc
  * Table slicing
    * ตัดมาเฉพาะ column ที่ต้องการ
    * ตัดเฉพาะ rows ที่ต้องการ
  * ตรวจสอบ missing ( isnull() )
    * 1.ให้ได้ผลลัพธ์การจัดการ dropna() ต้องเอาตัวแปรมารับ
    * 2.update ตารางด้วยตัวแปร  inplace
    * แทน missing ด้วยค่าที่เหมาะสม (fillna)
      * 1.แทนด้วย class ใหม่
      * 2.แทนด้วยค่าที่เหมาะสม
        * แทนด้วยค่ากลาง
     * การวนลูป record ในตาราง (.iterrows)
     * การวนลูป แบบมองตารางแพนด้าส์(pandas dataframe) เป็น numpy array (.iloc)
     * 
  * Function ตัวช่วยใน pandas
    * .describe() คำนวณค่าทางสถิติของข้อมูลที่เป็นตัวเลข
    * .mean() คำนวณค่าเฉลี่ยของข้อมูลโดยไม่สนใจ missing
    * .isnull() ตรวสอบค่า missing

* [Pandas102](https://github.com/mintra-tippayaratsontorn/data_viz_2022/blob/main/Pandas102.ipynb)
  * ต่อตาราง
    * ต่อแกน Y
    * ต่อแกน X
  * Save Table
  * Groupby
  * Create Pandas table
    * Dictionary (row oriented)
    * List (row oriented)
    * Dictionary (column orientrd)
    * List (column orientrd)
