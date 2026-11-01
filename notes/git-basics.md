# Git ke Basic Commands

Git ek tool hai jo aap ke code ki history ko save karta hai aur doosron ke saath mil kar kaam karna asaan banata hai. Yahan 5 basic commands simple Urdu mein samjhaye gaye hain.

## 1. `git init`

**Matlab:** Is command se kisi folder mein naya Git repository shuru hota hai. Yani Git ko bataya jata hai ke is folder ki history save karni hai.

**Misaal:**

```bash
mkdir mera-project
cd mera-project
git init
```

Is ke baad folder mein ek chhupa hua `.git` folder ban jata hai.

## 2. `git add`

**Matlab:** Is command se aap batate hain ke kaun si files agle commit mein shamil karni hain. Isay "staging area" mein file rakhna kehte hain.

**Misaal:**

```bash
git add index.html      # sirf ek file
git add .               # tamam badli hui files
```

## 3. `git commit`

**Matlab:** Is command se staging area ki files ka ek snapshot (save point) ban jata hai, saath mein ek chhota sa message hota hai jo batata hai ke kya badla.

**Misaal:**

```bash
git commit -m "Pehla page bana diya"
```

## 4. `git push`

**Matlab:** Is command se aap ke local commits internet par remote repository (jaise GitHub) par upload ho jate hain.

**Misaal:**

```bash
git push origin main
```

Yahan `origin` remote ka naam hai aur `main` branch ka naam hai.

## 5. `git pull`

**Matlab:** Is command se remote repository ki nayi tabdiliyan download ho kar aap ke local code mein mil jati hain. Doosron ka kaam apne paas lene ke liye istemal hota hai.

**Misaal:**

```bash
git pull origin main
```

## Khulasa

| Command | Kaam |
|---------|------|
| `git init` | Naya repository shuru karna |
| `git add` | Files ko commit ke liye tayyar karna |
| `git commit` | Changes ko save karna |
| `git push` | Changes ko remote par bhejna |
| `git pull` | Remote se changes lena |
