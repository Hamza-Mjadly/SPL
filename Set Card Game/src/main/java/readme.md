## README for Hadoop and AWS EMR Project

## Project Information
- **Name:** Hamza Mjadly
- **ID:**   325043552     
 
- **Name:** Aseel Biadsi
- **ID:** 213758758

---

## How to Run the Project

### Prerequisites
1. **AWS Account**: Ensure you have an active AWS account.
2. **EMR Cluster Setup**:
   - Launch an EMR cluster with the required configurations.
   - Use Hadoop version [specify the version].
   - Configure the necessary input/output paths in S3.
3. **Input Data**:
   - Upload your input data to the S3 bucket: `s3://[your-input-bucket-path]`
4. **Dependencies**:
   - Ensure all required dependencies are installed on the cluster or included in your project.

### Steps to Run
1. **Upload Code**: Upload the source code to the EMR cluster or S3.
2. **Execute the Job**:
   ```bash
   hadoop jar [your-jar-file.jar] [MainClassName] [input-path] [output-path]
3. **Monitor Progress**: Check the Hadoop logs on the EMR console for status updates.
4. **Output Data**: Output will be available in:
   ```bash
   s3://[your-output-bucket-path]

   
  ---

  ## Reports

  ### Key-Value analysis
  
  - Number of Key-Value Pairs (With Local Aggregation): 372,447,702
  - Size of Key-Value Pairs (With Local Aggregation): 64,594,624 
  - Number of Key-Value Pairs (Without Local Aggregation): 372,447,702
  - Size of Key-Value Pairs (Without Local Aggregation): 519,624,181 

   
  ---

  ## Scalability Report

  - **Input 1:**

    - **Run Times with Different Numbers of Mappers:**

      - Number of Mappers: 5
        -  Run Time: 30 minutes

      - Number of Mappers: 3/4
        -  Run Time: [B]

  - **Input 2**:

    - **Run Times with Different Numbers of Mappers:**

      - Number of Mappers: 5
        -  Run Time: [Y]

      - Number of Mappers: [A]
         - Run Time: [B]


  ## Word Pair Analysis

- **Interesting Word Pairs and Their Top-5 Next Words:**


**1.  Word Pair: אבא שלי**

- Top-5 Next Words: 
    -  אבא שלי אמר 0.15
    -  בא שלי אומר	0.09
    -  אבא שלי מת	0.051
    -  אבא שלי ואני	0.043
    -  אבא שלי סיפר	0.034

**2.  Word Pair: במלחמת העולם**

- Top-5 Next Words:
    - במלחמת העולם הראשונה	0.369
    - במלחמת העולם השנייה	0.241
    - במלחמת העולם השניה	0.152
    - במלחמת העולם האחרונה	0.004
    - במלחמת העולם הקודמת	0.002
**3.  Word Pair: אברהם אבן**

- Top-5 Next Words:
    - אברהם אבן עזרא	0.604
    - אברהם אבן דאוד	0.032
    - אברהם אבן שושן	0.015
    - אברהם אבן גאון	0.011
    - אברהם אבן חסדאי	0.01

**4.  Word Pair: אולי כדאי**

- Top-5 Next Words:
    - אולי כדאי להזכיר	0.134
    - אולי כדאי לך	0.114
    - אולי כדאי לציין	0.102
    - אולי כדאי גם	0.087
    - אולי כדאי לנסות	0.078

**5.  Word Pair: אולם אינני**

- Top-5 Next Words: 
    - אולם אינני יכול	0.31
    - אולם אינני רואה	0.186
    - אולם אינני רוצה	0.154
    - אולם אינני סבור	0.14
    - אולם אינני בטוח	0.121


**6.  Word Pair: בדומה לזה**

- Top-5 Next Words:
    - בדומה לזה גם	0.131
    - בדומה לזה אנו	0.099
    - בדומה לזה כתב	0.087
    - בדומה לזה כותב	0.05
    - בדומה לזה שהיה	0.043
  
**7.  Word Pair: בדומה לכך**

- Top-5 Next Words:
    - בדומה לכך גם	0.192
    - בדומה לכך אנו	0.098
    - בדומה לכך אפשר	0.068
    - בדומה לכך כותב	0.061
    - בדומה לכך כתב	0.06
  
**8.  Word Pair: ערב מלחמת**

- Top-5 Next Words:
    - ערב מלחמת העולם	0.529
    - ערב מלחמת ששת	0.226
    - ערב מלחמת יום	0.068
    - ערב מלחמת העצמאות	0.066
    - ערב מלחמת השחרור	0.028

**9.  Word Pair: עשרה שעות**

- Top-5 Next Words: 

    - עשרה שעות ביום	0.138
    - עשרה שעות ביממה	0.085
    - עשרה שעות רצופות	0.057
    - עשרה שעות הוי	0.0298
    - עשרה שעות עבודה	0.029
  
**10.  Word Pair: שלא נמצא**

-  Top-5 Next Words: 

    - שלא נמצא בשום	0.05
    - שלא נמצא להן	0.039
    - שלא נמצא שום	0.033
    - שלא נמצא פסול	0.032
    - שלא נמצא כלל	0.024
 

**Conclusion: we belive the results are very logical and the propotions seem to be correct.**

---

## Map-Reduce Steps:

**Step 1:**
  - k,,k,


**Step 2:**
  - k,,k,
    
**Step 3:**
  - Total words count
    
**Step 4:**
  - Join
    
**Step 5:**
  - Sort the results


    
   
