# ViWikiSum Dataset
4313 Vietnamese clusters for multi-text summaries </br>
Author team: [Huong Le-Thanh](mailto:huonglt@soict.hust.edu.vn), [Tuyen Dam-trong](mailto:damtrongtuyen1999@gmail.com), [Hieu Tran-Trung](mailto:hieutt99@gmail.com), [Thang Le-Dai](mailto:thangld.bkhn@gmail.com)

**Data construction process**

Data is collected automatically, with original texts (text used as summary) collected from pages with Vietnamese content from Wikipedia, on a number of predetermined topics. Reference texts (source texts used for summary) are articles obtained from a Google search with the search term being the title of the corresponding Wikipedia page. After cleaning, removing duplicate text or content unrelated to Wikipedia articles, from 10.000/500.000 article links collected on Wikipedia, we obtained 4313 Vietnamese text clusters, Each cluster has at least 2 source documents.

**Data Information**
- The `source` folder: Contains 4313 main subdirectories, which are 4313 text clusters, in each text cluster are documents belonging to the same topic. Each cluster contains 2-10 documents.
- Directory `summary`: Contains 4313 subdirectories, each containing a summary text of the documents in the corresponding cluster.

=> This corpus can be used as a standard corpus to serve the process of evaluating results for studies on multi-text summaries in Vietnamese.
This repo is the prototype of the ViWikiSum dataset we built. The full dataset after collecting 500,000 Wikipedia article links will be updated at [here](LINK_DRIVE)

--------------

# Bộ dữ liệu ViWikiSum
4313 cụm văn bản Tiếng Việt cho tóm tắt đa văn bản </br>
Nhóm tác giả: [Huong Le-Thanh](mailto:huonglt@soict.hust.edu.vn), [Tuyen Dam-Trong](mailto:damtrongtuyen1999@gmail.com), [Hieu Tran-Trung](mailto:hieutt99@gmail.com), [Thang Le-Dai](mailto:thangld.bkhn@gmail.com) 

**Quá trình xây dựng dữ liệu**

Dữ liệu được thu thập tự động, với các văn bản gốc(văn bản sử dụng làm văn bản tóm tắt) được thu thập từ các trang có nội dung Tiếng Việt từ Wikipedia, ở một số chủ đề định trước. Các văn bản tham chiếu (văn bản nguồn sử dụng cho việc tóm tắt) là các bài viết thu được từ quá trình tìm kiếm trên Google với từ khóa tìm kiếm là tiêu đề của trang Wikipedia tương ứng. Sau quá trình làm sạch, loại bỏ văn bản trùng lặp hay có nội dung không liên quan tới bài viết trên Wikipedia, từ 10.000/500.000 đường dẫn bài viết đã thu thập trên Wikipedia, chúng tôi thu được 4313 cụm văn bản Tiếng Việt, mỗi cụm có ít nhất 2 văn bản nguồn.

**Thông tin dữ liệu**
- Thư mục `source`: Chứa các 4313 thư mục con chính là 4313 cụm văn bản, trong mỗi cụm văn bản là các văn bản thuộc cùng 1 chủ đề. Mỗi cụm chứa từ 2-10 văn bản.
- Thư mục `summary`: Chứa 4313 thư mục con mỗi thư mục chứa 1 văn bản tóm tắt của các văn bản trong cụm tương ứng.

=> Bộ ngữ liệu này có thể được sử dụng như là một nguồn ngữ liệu chuẩn để phục vụ quá trình đánh giá kết quả cho các nghiên cứu về tóm tắt đa văn bản trên Tiếng Việt.
Repo này là bản prototype của bộ dữ liệu ViWikiSum do chúng tôi xây dựng. Bộ dữ liệu đầy đủ sau khi xử lý thu thập 500.000 đường dẫn bài viết Wikipedia sẽ được cập nhật tại [đây](LINK_DRIVE)
