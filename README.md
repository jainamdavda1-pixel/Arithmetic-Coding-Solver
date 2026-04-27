# 🧮 Arithmetic Coding Solver (With Visualization)

An interactive web-based tool that demonstrates **Arithmetic Coding** by encoding messages step-by-step along with **visual interval diagrams**.

---

## 🚀 Features

- 🔢 Encode messages using arithmetic coding
- 📊 Step-by-step interval calculation display
- 📉 Dynamic **visual bar diagrams** for each step
- 🎯 Clean and interactive UI
- ⚡ Real-time computation

---

## 🛠️ Tech Stack

- **HTML** – Structure  
- **CSS** – Styling (Dark themed UI)  
- **JavaScript** – Logic and algorithm implementation  

---

## 📂 Project Structure


index.html (Contains HTML, CSS, and JavaScript)


---

 

---

## 🧠 How It Works

1. User inputs symbol probabilities  
   Example:

a:0.2,e:0.3,i:0.1,o:0.2,u:0.2


2. Probabilities are converted into cumulative ranges  

3. Initial range starts from:

[0, 1)


4. For each character in the message:
- Range is narrowed using symbol probabilities  
- New interval is calculated  
- A visual bar is generated  

5. Final encoded value is:

(low + high) / 2


---

## 📊 Visualization

- Each step is represented using a **horizontal bar**
- Shows how the interval shrinks after each symbol
- Helps understand compression visually

---

## 🧪 Example

**Input:**

Probabilities: a:0.2,e:0.3,i:0.1,o:0.2,u:0.2
Message: eaii


**Output:**
- Final Range: [low, high)  
- Encoded Value  
- Step-by-step calculations  
- Visual diagram  

---

## 🛠️ How to Run

### Option 1: Run Locally
Just open:

index.html


---

 

---

## 📌 Future Improvements

- Add **decoding functionality**
- Allow dynamic probability generation
- Improve UI with animations
- Convert to React-based application
- Add error handling for invalid inputs

---

## 👨‍💻 Author

**Jainam Davda**  
🔗 https://github.com/jainamdavda1-pixel  

---

## ⭐ Support

If you found this project useful, give it a ⭐ on GitHub!
