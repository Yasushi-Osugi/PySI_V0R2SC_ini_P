# PySI_V0R2SC_ini_P
initial setting for PySI_V0R2SC_main_P. that is, creating node_all directory and setting 3 initial PSI files. 

各処理の詳細、入力・出力ファイルについては、
別資料「PySI 主要処理プロセス　一覧.pdf」を参照。


# ******************************
# パッケージ PySI_V0R2SC_ini_P　サプライチェーン用の初期環境の生成方法
# ******************************
【初期処理】

1. PySI_create_node_dir_copy_prof.pyを起動すると
   PySIのSCMTREE用の初期環境を生成する。

注)すべてのnodeディレクトリーを初期設定するので、要注意。
   稼働している環境ではなく、新しいディレクトリを作成して初期化するのが望ましい


   1-1. 各事業拠点のnode名のディレクトリをmkdirで作成する。

   1-2. PSIの3つのァイルをcopyする。
   ディレクトリ.\\data下の3入出力フファイルを\node_all下の各\node下にcopyする
   PySI_data_std_IO.csv
   PySI_Profile_std.csv
   PySI_monitor.xlsx

   1-3. 各事業拠点のnode毎に定義されたPSI計画パラメータprofileのサマリー表
        "SCMTREE_profile010.csv"を読み込んで、
        \node_allの下の各profileにcopyする
   

