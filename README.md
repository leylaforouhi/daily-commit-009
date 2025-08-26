def word_count(text):
    words = text.split()
    return len(words)

if __name__ == "__main__":
    sample = "GitHub helps developers build together"
    print(f"Word count: {word_count(sample)}")
