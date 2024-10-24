# Linux Administrator

## List all the files that the folder contains. 

```
ls [folder]
```

![image](https://github.com/user-attachments/assets/8fc8cc0a-0c09-474c-a469-2b515dcb79dc)

## Compared to the plain ls command, this returns much more information.

```
ls -al [folder]
```

![image](https://github.com/user-attachments/assets/8f3e4b2b-9a3f-4cc0-9478-d4e40567da3d)

## Create folders 

```
mkdir [folder name]
```

![image](https://github.com/user-attachments/assets/7d636afe-efba-4c88-8f0c-d6eb428b1624)

## Create multiple nested folders 

```
mkdir -p [parent folder]/[child folder]
```

![image](https://github.com/user-attachments/assets/3c58bdce-d1ef-4f2a-b060-876b2e5a75a6)

## Move into or change directory.

```
cd [folder name] 
```

![image](https://github.com/user-attachments/assets/2a146c75-3806-4281-aa67-4a0e59d7d710)

## Move into or change multiple directory.

```
cd [parent folder]/[child folder] 
```

![image](https://github.com/user-attachments/assets/3a816e64-c50c-4399-a70f-5c6ff76a96b1)

### Back to parent directory

```
cd ..
```

![image](https://github.com/user-attachments/assets/9ed4d415-e658-4367-9add-0d3a24142b6d)

```
cd ../..
```

![image](https://github.com/user-attachments/assets/85fb75ad-294b-4c36-976d-7d6142ef541a)

## Back to parent and move another directory 

```
cd ../[another folder]
```

![image](https://github.com/user-attachments/assets/a6dc5974-b4ba-4bdf-9cce-9b18df986c84)

## To know the current folder 

```
pwd
```

![image](https://github.com/user-attachments/assets/54ef0adf-18ed-472f-8f4a-564493bd0cab)

## Delete a folder

```
rmdir [nama folder]
```

![image](https://github.com/user-attachments/assets/df6d4347-afa9-4e12-ba69-20f191226cc6)

## Delete multiple folders

```
rmdir [nama folder] [nama folder]
```

![image](https://github.com/user-attachments/assets/8cd84420-c6bb-46d4-bad8-7bbee0724488)

## Delete a folder with files in them

```
rm -rf [nama folder]
```

![image](https://github.com/user-attachments/assets/32832362-9b94-499b-9b39-1f67085359fe)

## Move files to another folder 

```
mv [nama file] [nama folder]
mv [nama file] [nama file] [nama folder]
```

![image](https://github.com/user-attachments/assets/d4618bac-12a0-49ec-abde-052a1de57448)

![image](https://github.com/user-attachments/assets/11cf9303-b848-44a2-9954-2a71ac2459c3)

## Create file and multiple file 

```
touch [nama file] 
touch [nama file] [nama file] 
```

![image](https://github.com/user-attachments/assets/150ea9c3-f93a-4af0-a926-0b9141168b55)

## Copy file to folder and folder to folder  

```
cp [nama file] [nama folder]
cp -r [nama folder] [nama folder tujuan] 
```

![image](https://github.com/user-attachments/assets/f451ea0e-fb1b-4047-8e2a-efd83214773f)

![image](https://github.com/user-attachments/assets/b8b46e2a-ae2d-4d5e-88cc-117977f955e8)

## compress a file using the gzip compression  

```
-- zip file with delete file
gzip [nama file]
-- zip file and no delete file  
gzip -c [filename] > [filename.gz]
-- zip multiple file
gzip [filename1] [filename2]
-- zip all file in folder 
gzip -r [foldername]
-- decompress file 
gzip -d [filename]
```

![image](https://github.com/user-attachments/assets/491eabdb-f44f-474b-8c48-f24fa3da2d62)

![image](https://github.com/user-attachments/assets/a0422224-d1b0-4cb9-bd6d-836f22054a03)

![image](https://github.com/user-attachments/assets/8bf2ebc8-b4b0-4750-b481-7244656bd459)

![image](https://github.com/user-attachments/assets/d090f26a-1187-45ad-8524-10645391b01d)

![image](https://github.com/user-attachments/assets/95145052-2bac-4764-8c15-2078b2146556)

