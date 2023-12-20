def create_readme(name, email, linkedin):
    """
    Generate a GitHub README content.

    :param name: Muhammet P.
    :param email: mpolat@e-cloud.web.tr
    :param linkedin: https://www.linkedin.com/in/muhammetpolat
    :return: README content as a string
    """
    content = f"""
# Hello, I'm {name}! 👋

Welcome! You've stepped into my virtual workspace where you can discover my passion for technology.

## 🚀 About Me
I am a developer specialized in Python, PHP, and JavaScript. I love exploring technology and pushing the boundaries of software.

### 🧠 My Expertise
- **Blockchain:** Shaping the future of blockchain technology and exploring new frontiers in this revolutionary field.
- **Artificial Intelligence:** Creating intelligent solutions using the power of AI.
- **Cybersecurity:** Continuously researching new methods to ensure the safety of the digital world.

## 💬 Contact
Feel free to reach out to me! I always enjoy discussing new ideas and projects.

- 📧 Email: {email}
- 🔗 LinkedIn: {linkedin}
"""
    return content


my_readme = create_readme("Your Name", "mpolat@e-cloud.web.tr", "https://www.linkedin.com/in/muhammetpolat")


print(my_readme)
