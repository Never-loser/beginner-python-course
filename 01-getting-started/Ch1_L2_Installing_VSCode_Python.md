# Chapter 1 — Lesson 2
# Installing Python and VS Code

---

## 🇬🇧 English

### 1. What We Are Installing, and Why
We need three things:
1. **Python itself** — the "engine" that runs your code.
2. **VS Code** (Visual Studio Code) — a free, lightweight code editor.
3. **Two VS Code extensions**: *Python* and *Jupyter* (both by Microsoft) — these turn VS Code into a full Python + notebook environment.

> We are **not** using Anaconda in this course. Plain Python + VS Code is lighter, and closer to what you'll use in most real jobs.

### 2. Installing Python

**Windows**
1. Go to `https://www.python.org/downloads/`
2. Download the latest Python 3 installer.
3. Run it. **Important:** check the box **"Add python.exe to PATH"** before clicking Install.
4. Open Command Prompt (`cmd`) and type `python --version`. You should see something like `Python 3.12.x`.

**macOS**
1. Go to `https://www.python.org/downloads/` and download the macOS installer, or install via Homebrew: `brew install python`.
2. Open Terminal and type `python3 --version`.

**Linux**
Most distros already ship with Python 3. Check with `python3 --version`. If missing: `sudo apt install python3` (Debian/Ubuntu-based).

### 3. Installing VS Code
1. Go to `https://code.visualstudio.com/`
2. Download and install for your OS (default options are fine).
3. Open VS Code.

### 4. Installing the Python & Jupyter Extensions
1. Click the **Extensions** icon in the left sidebar (or `Ctrl+Shift+X`, `Cmd+Shift+X` on Mac).
2. Search **"Python"** (by Microsoft) → **Install**.
3. Search **"Jupyter"** (by Microsoft) → **Install**.
4. Restart VS Code.

### 5. Verifying Everything Works
1. Create a new folder for this course.
2. Open it in VS Code (`File > Open Folder`).
3. Create a new file named `test.ipynb`.
4. VS Code opens it as a notebook. Click **Select Kernel** (top-right) and choose your installed Python.
5. In the first cell type `print("It works!")` and press `Shift+Enter`. If output appears below the cell — you're done.

### Exercises

**🟢 Easy**
Open your terminal and run **both**:
```
python --version
```
(or `python3 --version` on Mac/Linux), then:
```
echo "YOUR FULL NAME - TODAY'S DATE"
```
Take **one screenshot showing both commands and their output together**, with your real name and today's real date visible. Submit the screenshot.
> Because it must show your real name and today's actual date, this screenshot cannot be copied from anyone else — it proves you verified the install yourself, today.

**🟡 Medium**
On purpose, reinstall Python **without** checking "Add to PATH" (or manually remove Python from PATH) so that running `python --version` in a **new** terminal window fails. Screenshot the **exact error message**. Then, in 2–3 sentences, in your own words, explain what PATH means and how you fixed it so `python --version` works again.

**🔴 Hard**
Create a Python **virtual environment** whose name includes your own name or student ID, e.g.:
```
python -m venv venv_<your_name_or_id>
```
In VS Code, open the interpreter/kernel selector for a notebook and pick this custom-named environment. Screenshot the interpreter list **with your custom environment visibly selected**.
> Since the environment name must contain your own name/ID, this can't be reused from a classmate's screenshot — and creating it requires actually running the command yourself.

---

## 🇮🇷 فارسی

### ۱. چه چیزهایی نصب می‌کنیم و چرا
به سه چیز نیاز داریم:
۱. **خود پایتون** — موتوری که کد شما را اجرا می‌کند.
۲. **VS Code** — یک ویرایشگر کد رایگان و سبک.
۳. **دو افزونه‌ی VS Code**: *Python* و *Jupyter* (هر دو از مایکروسافت) — این‌ها VS Code را به یک محیط کامل پایتون + نوت‌بوک تبدیل می‌کنند.

> در این دوره از **آناکندا استفاده نمی‌کنیم**. پایتون خام + VS Code سبک‌تر است و به محیط کار واقعی نزدیک‌تر.

### ۲. نصب پایتون

**ویندوز**
۱. به `https://www.python.org/downloads/` بروید.
۲. آخرین نسخه‌ی پایتون ۳ را دانلود کنید.
۳. نصب‌کننده را اجرا کنید. **مهم:** پیش از کلیک روی Install، گزینه‌ی **«Add python.exe to PATH»** را تیک بزنید.
۴. Command Prompt (`cmd`) را باز کرده و بنویسید `python --version`. باید چیزی شبیه `Python 3.12.x` ببینید.

**مک**
۱. به `https://www.python.org/downloads/` بروید و نسخه‌ی مک را دانلود کنید، یا با Homebrew نصب کنید: `brew install python`.
۲. ترمینال را باز کرده و بنویسید `python3 --version`.

**لینوکس**
اکثر توزیع‌ها از قبل پایتون ۳ دارند. با `python3 --version` چک کنید. اگر نبود: `sudo apt install python3`.

### ۳. نصب VS Code
۱. به `https://code.visualstudio.com/` بروید.
۲. متناسب با سیستم‌عاملتان دانلود و نصب کنید (گزینه‌های پیش‌فرض کافی است).
۳. VS Code را باز کنید.

### ۴. نصب افزونه‌های Python و Jupyter
۱. روی آیکن **Extensions** در نوار کناری سمت چپ کلیک کنید (یا `Ctrl+Shift+X`؛ در مک `Cmd+Shift+X`).
۲. عبارت **"Python"** (از مایکروسافت) را جستجو و **Install** بزنید.
۳. عبارت **"Jupyter"** (از مایکروسافت) را جستجو و **Install** بزنید.
۴. VS Code را ری‌استارت کنید.

### ۵. تست اینکه همه‌چیز درست کار می‌کند
۱. یک پوشه‌ی جدید برای این دوره بسازید.
۲. آن را در VS Code باز کنید (`File > Open Folder`).
۳. یک فایل جدید با نام `test.ipynb` بسازید.
۴. VS Code آن را به‌صورت نوت‌بوک باز می‌کند. روی **Select Kernel** (بالا سمت راست) کلیک کرده و پایتون نصب‌شده‌تان را انتخاب کنید.
۵. در اولین سلول بنویسید `print("It works!")` و `Shift+Enter` بزنید. اگر خروجی زیر سلول ظاهر شد — تمام است.

### تمرین‌ها

**🟢 آسان**
ترمینال را باز کنید و **هر دو** دستور را اجرا کنید:
```
python --version
```
(یا در مک/لینوکس: `python3 --version`)، سپس:
```
echo "نام کامل شما - تاریخ امروز"
```
**یک اسکرین‌شات** بگیرید که هر دو دستور و خروجی‌شان با هم دیده شود، طوری‌که نام واقعی و تاریخ واقعیِ امروز در خروجی echo دیده شود. اسکرین‌شات را ارسال کنید.
> چون باید نام واقعی و تاریخ واقعی امروز دیده شود، این اسکرین‌شات از روی کس دیگری قابل کپی نیست و ثابت می‌کند خودتان همین امروز نصب را تست کرده‌اید.

**🟡 متوسط**
عمداً پایتون را **بدون** تیک‌زدن «Add to PATH» دوباره نصب کنید (یا پایتون را از PATH حذف کنید) تا اجرای `python --version` در یک پنجره‌ترمینال **جدید** خطا بدهد. از **متن دقیق خطا** اسکرین‌شات بگیرید. سپس در ۲ تا ۳ جمله، با کلمات خودتان، توضیح دهید PATH چیست و چطور مشکل را برطرف کردید تا دوباره `python --version` کار کند.

**🔴 سخت**
یک **محیط مجازی (virtual environment)** بسازید که نامش شامل نام یا شماره‌دانشجویی خودتان باشد، مثلاً:
```
python -m venv venv_نام_یا_آیدی_شما
```
در VS Code، منوی انتخاب مفسر/کرنل را برای یک نوت‌بوک باز کنید و همین محیط با نام سفارشی را انتخاب کنید. از لیست مفسرها اسکرین‌شات بگیرید، **طوری‌که محیط سفارشی‌تان به‌وضوح انتخاب‌شده دیده شود**.
> چون نام محیط باید شامل نام/آیدی خودتان باشد، این اسکرین‌شات از روی اسکرین‌شات یک هم‌کلاسی قابل استفاده نیست، و ساختنش نیازمند اجرای واقعی دستور در ترمینال است.
