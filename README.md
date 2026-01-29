<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eva - متجر العناية والمكياج العراقي</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;500;600;700&family=Scheherazade+New:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Cairo', sans-serif;
        }
        
        :root {
            --primary-color: #f8a5c2; /* وردي فاتح */
            --secondary-color: #c44569; /* وردي داكن */
            --accent-color: #786fa6; /* بنفسجي */
            --light-color: #fff5f9; /* وردي فاتح جداً */
            --neutral-color: #f7d794; /* بيج فاتح */
            --text-color: #574b90; /* بنفسجي داكن للنصوص */
            --shadow: 0 5px 15px rgba(120, 111, 166, 0.1);
            --admin-color: #2d4059; /* أزرق داكن للوحة التحكم */
        }
        
        body {
            background-color: var(--light-color);
            color: var(--text-color);
            line-height: 1.6;
        }
        
        /* زر لوحة التحكم */
        .admin-toggle {
            position: fixed;
            bottom: 20px;
            left: 20px;
            background-color: var(--admin-color);
            color: white;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
            cursor: pointer;
            z-index: 9999;
            box-shadow: 0 4px 12px rgba(45, 64, 89, 0.3);
            transition: all 0.3s ease;
        }
        
        .admin-toggle:hover {
            transform: scale(1.1);
        }
        
        /* الهيدر */
        header {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            padding:
