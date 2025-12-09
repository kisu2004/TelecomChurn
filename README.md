    print("F1 Score :", f1)

# 9️⃣ Accuracy Comparison Plot
plt.figure(figsize=(8, 4))
sns.barplot(x=model_names, y=accuracies, hue=model_names, palette="Blues", legend=False)
plt.title("Model Accuracy Comparison")
plt.ylim(0, 1)
plt.xticks(rotation=20)
plt.tight_layout()
plt.show()

# 🔟 F1 Score Comparison Plot
plt.figure(figsize=(8, 4))
sns.barplot(x=model_names, y=f1s, hue=model_names, palette="Greens", legend=False)
plt.title("Model F1 Score Comparison")
plt.ylim(0, 1)
plt.xticks(rotation=20)
plt.tight_layout()
plt.show()
