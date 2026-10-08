







-


     
"         
          #  

XXXXXXXXXXXXXXXXXXXXXXXXXXXX"
 ken {token}"}


---------------------------
CHIVE (quickest way to get the whole repo)
# ----------------------------
l = f"https://api.github.com/repos/{owner}/{repo}/zipball/{branch}"
s.get(zip_url, headers=head
)

# Unpack the zip into a local folder
zip_bytes = io.BytesIO(resp.content)
 zipfile.ZipFile(zip_bytes) as z:
    # The zip contains a top‑level folder like "owner-repo-<hash>"
    # Extract everything into a folder named after the repo
    extract_path = f"./{repo}"
    os.makedirs(extract_path, exist_ok=True)
   

print(f"✅  Repository '{owner}/{repo}' extracted to ./{repo}")
.

