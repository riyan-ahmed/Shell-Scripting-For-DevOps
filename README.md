# 🐚 Shell Scripting for DevOps

A hands-on repository documenting my journey of learning **Bash Shell Scripting for DevOps**.

This repository contains practical shell scripts, exercises, log-processing examples, and automation practice designed to build the scripting skills commonly used in **DevOps, Cloud, Linux, and Infrastructure Automation**.

---

## 🚀 About This Repository

Shell scripting is an important skill for DevOps engineers because it allows repetitive operational tasks to be automated.

Through this repository, I am practising how to use Bash to:

* Automate repetitive Linux tasks
* Work with variables and user input
* Use conditional statements
* Work with loops
* Create reusable functions
* Process files and logs
* Handle errors
* Execute Linux commands through scripts
* Build automation useful for DevOps workflows

---

## 📂 Repository Structure

```text
Shell-Scripting-For-DevOps/
│
├── day01/
├── day02/
├── day03/
├── log-files/
├── practice-scripts/
│
├── hello.sh
├── variables.sh
└── README.md
```

### 📘 `day01/`

Introduction to shell scripting and Bash fundamentals.

Topics include:

* Basic Bash syntax
* Running shell scripts
* Variables
* Printing output
* Command execution

### 📘 `day02/`

Continues into programming concepts used in Bash.

Topics include:

* Conditional statements
* Loops
* User input
* Arguments
* Basic automation logic

### 📘 `day03/`

More practical shell scripting and DevOps-focused exercises.

Focus areas include:

* Automation
* Error handling
* Linux administration
* Working with commands and services
* Practical scripting scenarios

### 🧪 `practice-scripts/`

A collection of scripts created while practising Bash concepts.

The goal of this directory is to move from basic syntax toward scripts that can automate real operational tasks.

### 📊 `log-files/`

Sample log files used to practise Linux text-processing and troubleshooting commands such as:

```bash
grep
awk
sed
cut
sort
uniq
head
tail
```

Log analysis is particularly useful in DevOps when troubleshooting applications, servers, containers, and CI/CD systems.

---

## 🛠️ Technologies & Tools

* **Bash**
* **Linux**
* **Shell Scripting**
* **Git**
* **GitHub**
* **Linux CLI**
* **AWS CLI**
* **Docker**
* **Cron**
* **grep / awk / sed**

---

## 🧠 Concepts Covered

### Variables

```bash
name="Riyan"
location="London"

echo "My name is $name"
echo "Location: $location"
```

### User Input

```bash
read -p "Enter your name: " name
echo "Hello $name"
```

### Conditions

```bash
if [ "$1" == "start" ]; then
    echo "Starting service..."
else
    echo "Unknown command"
fi
```

### For Loops

```bash
for server in server1 server2 server3
do
    echo "Checking $server"
done
```

### Functions

```bash
check_service() {
    echo "Checking service status..."
}
```

### Command Substitution

```bash
current_date=$(date)

echo "Current date: $current_date"
```

---

## ⚙️ Running the Scripts

Clone the repository:

```bash
git clone https://github.com/riyan-ahmed/Shell-Scripting-For-DevOps.git
```

Move into the project:

```bash
cd Shell-Scripting-For-DevOps
```

Give a script execution permission:

```bash
chmod +x script.sh
```

Run it:

```bash
./script.sh
```

Alternatively:

```bash
bash script.sh
```

---

## 🐛 Debugging Shell Scripts

Bash scripts can be debugged using:

```bash
bash -x script.sh
```

You can also check the exit status of the previous command:

```bash
echo $?
```

A return value of:

```text
0
```

normally indicates that the command completed successfully.

---

## 💡 Why Shell Scripting Matters in DevOps

Shell scripting can be used to automate tasks such as:

* Server configuration
* Application deployment
* Log analysis
* System monitoring
* User management
* Package installation
* Backup automation
* Docker operations
* Cloud resource management
* CI/CD pipeline tasks
* Scheduled jobs using Cron

Instead of manually repeating commands, DevOps engineers can turn them into reusable scripts.

---

## 🎯 Learning Goal

The aim of this repository is to develop strong Bash scripting fundamentals and progress toward writing reliable automation for real DevOps environments.

The learning path is:

```text
Bash Fundamentals
       ↓
Variables & Input
       ↓
Conditions
       ↓
Loops
       ↓
Functions
       ↓
Files & Logs
       ↓
Error Handling
       ↓
Linux Automation
       ↓
DevOps Automation
```

---

## 🔮 Future Improvements

As I continue learning, I plan to add scripts covering:

* System health monitoring
* Disk and memory monitoring
* Automated backups
* User management
* Package installation
* Service monitoring
* Docker automation
* AWS automation using AWS CLI
* Log monitoring and alerting
* Cron job automation
* Deployment automation

---

## 👨‍💻 Author

**Riyan Ahmed**

DevOps | Cloud | Platform Engineering

GitHub: [riyan-ahmed](https://github.com/riyan-ahmed)

---

## ⭐ Repository Purpose

This repository is part of my hands-on DevOps learning journey.

Rather than only studying shell scripting concepts theoretically, the focus is on **writing, testing, debugging, and improving scripts through practical exercises**.

If you find the repository useful, feel free to ⭐ the project.

