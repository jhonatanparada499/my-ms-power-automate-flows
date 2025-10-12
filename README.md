# My Power Automate Flows

![OneDrive](https://img.shields.io/badge/OneDrive-white?style=for-the-badge&logo=Microsoft%20OneDrive&logoColor=0078D4)
![Microsoft](https://img.shields.io/badge/Microsoft-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Microsoft Office](https://img.shields.io/badge/Microsoft_Office-D83B01?style=for-the-badge&logo=microsoft-office&logoColor=white)
![Microsoft Word](https://img.shields.io/badge/Microsoft_Word-2B579A?style=for-the-badge&logo=microsoft-word&logoColor=white)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

This repository has the packages of my cloud flows exported as zip files from Microsoft Power Automate.  

## Cover Page Populator

This flow automates 3 common tasks when creating a lab report with images.  

The first task is to create a cover page, in which you would typically include your name, date, class name and so on. But, this flow can do that by leveraging a custom user template. Moreover, if you want to get fancy, you can even add dynamic information like the professor's name and class code in the cover page as well.  

The second task is to format the document, or make it look nice. In this case, just like the first task is addressed, a custom user template will include all the formatting settings like footer, headers, font and so on.  

The third task--which was the reason I created this flow--is making images snap perfectly in each page. Since I use Microsoft word in the web, I used to find myself limited when manipulating images and arranging them. I did not like to see huge gaps between pages. For example, I like a document that shows 2 images per page and that are evenly distributed. And if you use the default template of this repo, you will get that layout too.

The fourth and last task is to save the document to a custom folder in OneDrive.

### Preconditions

In order to make this flow right out of the box, you would need to have the following folders in your root directory of OneDrive: `Templates/ Courses/ Attachments/ Metadata/`

```
My files (root)
├── Templates
│   └── Lab_Report.docx
├── Courses
│   ├── ET726
│   ├── ET506
|   ├── PH112
│   └── ...
├── Attachments
│   ├── IMG_1.png
│   ├── IMG_2.png
│   └── ...
└── Metadata
    └── Classes_Info.xlsx
```


