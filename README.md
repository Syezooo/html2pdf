# dockerイメージのビルド
```
docker build -t html2pdf:ubuntu20.04 .
```

# dockerコンテナ起動
```
docker run -it --rm -v ${PWD}:/workspace -w /workspace html2pdf:ubuntu20.04
```

# 指定のhtmlファイルをpdf化
```
python3 html2pdf.py [ファイル名]
```
