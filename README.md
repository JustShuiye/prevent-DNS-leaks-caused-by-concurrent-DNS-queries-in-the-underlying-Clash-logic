只需要将文件内容复制后导入clash的脚本覆写，确保覆盖原节点配置，即可避免由clash底层逻辑的DNS并发查询导致的DNS泄露

Simply copy the file content and import it into the Clash script to overwrite the existing configuration, ensuring that the original node configuration is overwritten. This will prevent DNS leaks caused by concurrent DNS queries in Clash's underlying logic.

第二个代码旨在解决出现第一个代码无法解决的情况，其原理与第一个代码不同，仅做备用

The second code is designed to handle situations where the first code cannot resolve the issue. Its underlying principle differs from the first code, and it is intended as a backup.
