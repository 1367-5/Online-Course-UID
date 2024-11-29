# Online-Course-UID

## Unique Identifier (UID)

A unique identifier (UID) for an online course is a distinct code assigned to each specific course, and it can be used across all platforms that offer the course. This ensures that the course can be clearly identified by its UID regardless of the platform hosting it.

网课唯一标识符（UID）是一种分配给每门特定课程的独特代码，可以在所有提供该课程的平台上使用。这确保了无论该课程在哪个平台上托管，都可以通过其 UID 明确识别。

## UniqueID-Guidelines

本指南详细描述了如何生成和使用网课唯一标识符（UID），以确保在所有平台上对课程的唯一识别。

### 1. 国家代码（Country Codes）

国家代码由 3 个数字组成，参考国际标准化组织（ISO）3166-1 数字代码。请参阅 `country-codes.csv` 文件以获取完整的国家代码列表。

### 2. 学校代码（School Codes）

学校代码由 4 个数字组成，结合国家代码中的唯一学校编号。每个国家的学校代码在 `school-codes.csv` 文件中列出。

### 3. 年份（Year）

年份使用标准的四位数格式，例如 2023。

### 4. 专业代码（Subject Codes）

专业代码由 4 个字符组成，可以是数字或字母。每个专业的唯一编号或缩写在 `subject-codes.csv` 文件中列出。

### 5. 课程代码（Course Codes）

课程代码由 3 个字符组成，可以是数字或字母，用于标识具体课程。具体课程代码在 `course-codes.csv` 文件中列出。

### 示例

假设一个课程是 2023 年由美国的哈佛大学提供的一门计算机科学专业的课程，其 UID 为：001-0001-2023-0101-001

- 国家（美国）: 001
- 学校（哈佛大学）: 0001
- 年份（2023）: 2023
- 专业（计算机科学）: 0101
- 课程编号: 001

### 参考文件

- [country-codes.csv](country-codes.csv)
- [school-codes.csv](school-codes.csv)
- [subject-codes.csv](subject-codes.csv)
- [course-codes.csv](course-codes.csv)
